1. Onboarding is the top priority

Onboarding needs a full bug-fix and flow review.

Key items:

* Fix onboarding bugs.
* Review and clean up the onboarding state machine.
* Fix page navigation issues.
* Fix Google Sign-In button.
* Confirm paywall behavior works correctly.
* Make sure users can complete onboarding without getting stuck.

Outcome needed: onboarding should feel stable and production-ready.

⸻

2. Progress chart and weight log need UI and functionality fixes

Progress needs polish, especially around the chart and the weight log.

Key items:

* Make chart dots smaller.
* Ensure the chart line displays correctly in front of dots.
* Fix chart labels.
* Change “Daily Weight” so it appears as a legend, not a button.
* Fix the weight log infinite scroll issue.
* Allow users to tap a weight log entry and view notes/comments.
* Add an icon to show when a weight log has a note.
* Add a menstruation section to Progress.

Owner: Marc

⸻

3. General UI polish needs a pass

There are several app-wide UI improvements to clean up.

Key items:

* Update the Home heading so it sticks and shrinks on scroll.
* Add an animated “Add Weight” button separate from the tab bar.
* Decide whether Add Weight opens as a modal or pushed screen.
* Push Settings as a normal screen instead of presenting it as a modal.
* Validate and fix Settings bugs.
* Review app against Apple Human Interface Guidelines.

Owner: Jack

⸻

4. Home page needs to be updated from Figma

The Home page should be updated to match the latest Figma designs.

Key items:

* Apply latest UI changes from Figma.
* Polish spacing, typography, layout, and sections.
* Explore adding CMS articles to the Home page.
* Decide where CMS content should appear and how it should behave.

⸻

5. Database / fight camp structure needs a decision

There is an open question around whether the database needs to change to support more fight camps properly.

Main concern:

* Weight log is currently global.
* Need to decide whether weight logs should belong to a specific fight camp.

Key questions:

* Can users have multiple fight camps?
* Should weight logs be tied to a fight camp or user globally?
* How should historical fight camps work?
* What data should be global vs fight-camp-specific?

Outcome needed: decide whether database changes are required before building more fight camp features.

⸻

6. Plan page is currently blocked

The Plan page needs clarification before work continues.

Current understanding:

* Plan should summarise onboarding information.
* It may include historical fights and fight camp details.
* Need to check with Zoe on the actual scope.

Blocked by: confirmation from Zoe.

⸻

7. CMS needs exploration

Need to investigate CMS support for articles on the Home page.

Key items:

* Confirm CMS source.
* Define article fields.
* Decide how articles appear on Home.
* Define loading, empty, and error states.
* Decide whether articles open in-app or externally.

⸻

8. Settings needs validation

Need to confirm whether Settings updates actually save and behave correctly.

Key items:

* Test updating settings.
* Confirm changes persist after closing/reopening the app.
* Fix bugs found during testing.
* Move Settings from modal presentation to pushed navigation.

⸻

9. Push notifications are lower priority but need scoping

Push notifications need requirements before implementation.

Potential notification types:

* Daily weight reminder.
* Fight camp check-in.
* Plan reminder.
* Article/content notification.
* Progress milestone.
* Menstruation/cycle reminder.

Outcome needed: define what notifications are needed and when permission should be requested.