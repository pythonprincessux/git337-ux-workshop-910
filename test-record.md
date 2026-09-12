## Inclusive Form Test Record

**Student:** Kiara McRae  
**Project:** Community UX Workshop Registration

## Keyboard Navigation Test

**Test:** I navigated through the completed form using the keyboard.

**Result:** Pass

**Observation:** I was able to move through the form controls using the keyboard. All text inputs, select menus, radio buttons, checkboxes, textareas, and the submit button were keyboard accessible using the tab button and space bar. The gold focus visible focus indicator appeared while moving through the controls.

## Required Field Validation Test

**Test:** I attempted to submit the form while required fields were empty.

**Result:** Pass

**Observation:** The browser did not allow submission and displayed validation feedback for the missing required field.

## Invalid Email Test

**Test:** I entered an invalid email address and attempted to submit the form after completing the other required controls.

**Result:** Pass

**Observation:** The browser prevented submission and displayed email format validation feedback.

## GET Submission Test

**Test:** I completed and submitted the form using fake data.

**Test data:**
- Full name: Alex Morgan
- Email: alex@example.com
- Experience level: Beginner
- Workshop session: Morning
- Attendance format: In person
- Primary goal: Improve UX research skills
- Topics: UX research, Accessibility, Prototyping
- Confirmation: Checked

**Result:** Pass

**Observation:** After submission, the browser URL/query string had the expected name and value pairs for the completed controls. The optional accommodations and comments controls were left blank.

## Accessibility Tree Test

**Test:** I inspected representative form controls using Chrome DevTools accessibility tree  information by launching devtools, right clicking, and launching accessibility tree.

**Result:** Pass

**Observation:** The accessibility tree showed meaningful accessible names and groups. Full name and Email address were identified as required textboxes. UX experience level and Primary workshop goal were used as comboboxes. Preferred workshop session and Attendance format were used as groups. The optional UX topics group had individually named UX research, Accessibility, and Prototyping checkboxes.

## Evidence

I stored screenshots from the completed tests in the `evidence` folder.