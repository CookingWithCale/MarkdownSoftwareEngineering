# Contributing Guide

**1.** Ensure the bug was not already reported by by reading the [Issues](https://github.com/ABCOrg/XYZProject/issues).

**2.** Open `/docs/bug_report_template.md` and copy it's contents to the clipboard.

**3.** Create an issue, paste the template into the Issue body and fill it out.

## Feature Requests

**1.** Same as the instructions for submitting a bug report except with using `/docs/feature_request.md`.

### Completing Issues

**1.** Clone the repo and create a branch for the IssueNuber:

```Console
git clone https://github.com/ABCOrg/XYZProject.git
cd Script2
git checkout -b Issue123
```

**2.** Complete the issue with passing unit tests and submit the completed issue:

```Console
git add --all
git commit -m "ModuleID.Add feature XYZ. #123"
git push origin Issue123
```

**3.** Create a Pull Requesting using the `/docs/pull_request_template`

**4.** Get others to inspect your changes and merge the branch to the master.

**5.** Merge the branch, complete another ticket, and delete the old branch.

```Console
git checkout -b Issue125
git add --all
git commit "ModuleID.Fix feature ABC. #125"
git branch -d Issue123
```

## License

Copyright © 2020 [Kabuki Starship](https://kabukistarship.com).

This file and the folder and repository it is contained in are private and contain intellectual property, trade secrets, copyrighted material, and other protected works, the IP, that are the property of the IP Owner. You must get explicit permission from the IP Owner to possess, view, modify, share, duplicate, discuss, or publicly display the IP.
