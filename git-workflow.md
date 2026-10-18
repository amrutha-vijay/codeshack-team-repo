 Git Workflow for Team Collaboration

1. Create a Feature Branch
Each team member should work on a separate branch instead of making changes directly on `main`.

Example:
`git switch -c feature-name`

2. Check Repository Status
Use this command to see which files have changed:

`git status`

3. Stage Changes
Stage the file you want to include in your commit:

`git add git-workflow.md`

4. Commit Changes
Record your staged changes with a meaningful message:

`git commit -m "Add Git workflow documentation"`

5. Push Your Branch
Upload your branch and commits to GitHub:

`git push -u origin feature-name`

6. Open a Pull Request
Create a pull request on GitHub to propose merging your branch into `main`. Team members can review the changes before merging.

7. Good Team Practices
- Give branches clear names.
- Use descriptive commit messages.
- Work on your assigned branch.
- Review changes before merging.
- Avoid committing directly to `main`.

Conclusion
A consistent Git workflow helps team members work independently, track changes, review contributions, and collaborate safely.
