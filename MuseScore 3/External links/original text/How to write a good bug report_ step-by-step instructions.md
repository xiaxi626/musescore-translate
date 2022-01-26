### Isolate bug

The first step in in writing a bug report is to identify exactly what the problem is. Saying "something is wrong" is not helpful; saying exactly what is wrong, and how to reproduce it, is. If you can tell exactly what is wrong, and reliably reproduce an example of the problem, you've isolated a bug.

### Check if you are using the latest version

Bug reports should be based on the the latest [development build](/download#nightly). If you are using a released version or an out-of-date build, please update to the latest revision and check to see whether or not the bug still exists.

### Check if the bug is known

Please check whether the bug you are experiencing is already documented in the [issue tracker](/project/issues). If it is already documented, you may click "subscribe" to follow any developments. If your bug is different than any others recorded in the issue tracker, "Create a new issue".

### File each issue separately

If you have multiple issues, it is better to file them separately so they can be tracked more easily.

### Create a new issue

Sign into MuseScore.org and go to the [issue tracker](/project/issues) (a link is found on the right side of every page). Click on "[Create a new issue](/node/add/project_issue?pid=1236)".

There are a number of initial questions that are used for filing a bug report - answers to these allow progress.

### Title

The title should describe the problem as best as possible. Remember that the title is read more often than any other part of the bug report.

*Poor title*: Notes don't display correctly
This title is not specific enough for someone to look at it a month from now, and remember what the bug report is referring to.

*Good title*: Stems too short for 32nd and 64th notes
This title is an improvement over the previous title, because it specifies the type of notes that are affected and identifies the display problem.

After submitting the issue, it is possible to improve the title.

### Issue details

#### Project

The first question is which project your bug applies to. If in doubt, select "MuseScore", then "Next" to continue.

### Status

The status of new bug reports should generally be marked as "Active".

#### Reported Version

The version of MuseScore in which you discovered the bug (e.g., 3.0.2, or 3.0-dev). If you can reproduce the problem in more than one version, select the earliest.

#### Severity

Severity is the level of impact the bug has on the product.
There is something subjective about severity: when you choosing a level, always think about the product first. How much will the bug affect the core purpose of the product?
**S1 - Blocker** - The bug prevents a user from running/opening MuseScore.
**S2 - Critical** - The bug prevents the user from doing the intended action. They can’t go further. They're stopped. The bug prevents the user from using a key feature of MuseScore (e.g. layout, elements positions, mixer), there is no workaround, the business logic of a key feature doesn't work. There are security issues, data loss. **If MuseScore crashes, it's critical.**
**S3 - Major** - The bug is highly disturbing for the user but doesn’t prevent them from doing the action. The business logic of a key feature works wrong, but there is a workaround. The bug prevents the user from using a non-key feature of the software (e.g. navigator, timeline, piano roll). If there is a problem that causes the score to be unusable it is *at least* major and becomes critical if you can't open the score.
**S4 - Minor** - A bug in the UI which doesn't prevent usage of the features of the application. All other cases.
**S5 - Suggestion** - A suggestion is not a bug, so this means the product works faultlessly and in accordance with the predefined expectations. **However,** the reporter perceives it as confusing and/or the reporter thinks it does not conform with the standards, or the reporter may be suggesting a new feature for MuseScore.

#### Type

The type of a bug is the nature of a bug. This categorization is objective: a bug will always have the same nature for whatever product. Nevertheless, some bugs are tricky and you may struggle to choose between two categories. Type helps us to categorize and prioritize issues.
**Functional** - A dynamic bug related to an action you're doing. You can only find it while performing an action on a product. The product’s reaction is not as expected.
**Graphical bug (UI)** - A static bug related to UI (User Interface) issues.
**Wording bug** - A bug related to the text content, including translation issues
**Ergonomics (UX)** - An issue related to various user scenarios and proper placement of the UI elements
**Performance** - An issue related to the performance of the software
**Layout bug** - Everything related to displaying score, elements.
**musescore.org** - Issues related to the MuseScore editor website
**Plugins** - Issues related to QML plugins framework and related code in MuseScore
**Development** - Issues related to the code (although not functional issues - see above), infrastructure, deployment

**Frequency**
This category specifies whether the issue has been reported once or this is a frequent topic.
**Once** - 1 report in the issue tracker or forum
**Few** - 2-5 reports
**Many** - More than 5 reports

**Reproducibility**
This category defines whether the issue could be reproduced in a particular scenario.
**Always** - The steps to reproduce are probably easy to identify and to write. A scenario is always expected.
**Randomly** - The issue occurs only sometimes meaning that the conditions to reproduce the bugs are not yet identified, or that the conditions can only be reproduced randomly.
**Once** - The bug happened once and even reporter cannot reproduce it again

#### Regression

This category specifies whether the issue is a regression or not.
**Yes** - The bug cannot be reproduced in the previous version of the software, and/or the bug breaks the logic which works in a previous version.
**No** - The bug can be reproduced in the previous version of the software as well.

#### Workaround

This category defines whether there is an easy workaround for the issue.
**Yes** - There is easy (up to 3 steps) workaround for the reported bug. It means the user can perform the desired action using a different scenario.
**No** - There is no workaround to achieve the result.

#### Priority

Most bugs will be prioritized. This can only be done core team members. For reference, priorities are defined as follows:

Priority defines the importance of fixing the issue. The issues with high priority should be fixed first.
**P0 - Critical** - The issue must be fixed asap. Usually, this priority is used for the issues affecting development/deploy/infrastructure issues.
**P1 - High** - The issue should be fixed/implemented in the next release. These issues stop the release.
**P2 - Medium** - Nice to have this issue fixed/implemented in the next release. The issue won’t stop the release.
**P3 - Low** - The issue can be fixed/implemented, but if someone wants to do so, it is better to spend time on P1/P2 issues if you feel confident enough

### Description

#### Steps to reproduce bug


A bug report requires clear instructions, so that others can consistently reproduce it. Many bugs require some experimentation to find the exact steps that cause the problem you are trying to report. If you aren't able to discover these, try obtaining some help on the [forums](/forum) instead.

A good set of instructions includes a numbered list that details each button press, or menu selection. The following bug reports are good examples to mimic: 

*Note: the following bugs have all now been fixed*

* http://musescore.org/en/node/5870
* http://musescore.org/en/node/6479
* http://musescore.org/en/node/22789


It can also be helpful to test your own instructions, as though someone else is trying them (as they will).

#### Expected behavior

Describe what should happen if the bug was fixed.

#### Actual behavior

In contrast to the expected behavior, describe what currently happens when the bug is present.

#### Version number

In MuseScore, go to About (listed in a top menu, depending on your operating system) to find out the version of MuseScore you are using. For example: "Version: 2.0.0, Revision 6e47f74, Nightly Build".

In the development builds the commit code can be obtained via 'About' and clicking the 'Copy to clipboard' button (results in something like github-musescore-musescore-6e47f74, or in 'Help'>'Report a bug'.

Alternately, please state if you have compiled the source code and detail the versions of the third party tools.

#### Operating system

Name the operating system and version you are using, such as "Windows 8.1", or "macOS 10.15.1".

### File attachments

If you can supplement your bug report with an MSCZ score, image, audio, or crash log that helps others reproduce the issue, attach these files.
**NB:** After attaching a file with "Choose a file", remember to click "Insert" to add the necessary inline tags to the Issue description. Without this, the uploaded file will be discarded.
See also [node:289899,title="How To attach a file"]

### Submit

"Save" to submit your bug report to the issue tracker.

### Following up

Once a developer marks a bug as fixed, it is a good idea to ensure that it is completely fixed. To test,  download the latest [nightly build](/download#Development-builds).