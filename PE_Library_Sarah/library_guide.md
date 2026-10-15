# Library Guide · Member Services Desk at a Public Library
Owner of every file: Sarah · Date: 2026_10_15

## What is in the library
* `templates/`: five approved templates (reply, sort, soften a note, reminder, mask details).
* `blocks/`: the Library Facts. The only facts a template may use.
* `rules/`: the five fixed rules, already written inside each template.
* `library_index.md`: the list of templates, variables and status.
* `Test_Results_Report.pdf`: the three tests for each template.

## How to use a template
1. Open `library_index.md` and pick the template for your task.
2. Open the template file and copy everything under "TEMPLATE (copy from here)".
3. Replace each variable in square brackets with your value. The variables table in the file shows the allowed values and the default. If you leave a variable empty, the default is used.
4. Paste the filled prompt into the AI tool your organization approves.
5. Never paste real personal data. Run LB-Mask-Details first if a message contains it.

## How to check an output
Before sending anything, check that: every fact is in the Facts block; numbers, dates and names match the source; no promise is made and no action is claimed; no personal data is repeated; every question is answered and the wording reads naturally. A librarian reviews every message before it is sent.

## Who owns what
Sarah owns every file in this library. To change a template, copy the old version into `_archive/`, raise the version number and update the change log.
