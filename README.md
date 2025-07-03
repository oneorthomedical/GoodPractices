

## **Objective**

The objective of this document is to unify the source code of all Oneortho’s digital applications by adopting clear coding standards, structured version control practices, and efficient development workflows.

This will:
- Improve code readability and consistency.
- Make onboarding easier for new team members.
- Reduce bugs and simplify debugging.
- Ensure smooth collaboration between teams.

---

## **Wiki Summary**

1. [Code Best Practices](#code-best-practices)  
2. [Git Best Practices](#git-best-practices)  
3. [Git Rules](#git-rules)  
4. [Learn Git](#learn-git)  

---

## **Code Best Practices**

- Use meaningful variable and function names.  
  ✅ Example: `calculatePatientScore()` instead of `calcPS()`

- Follow PSR-12 coding standard for PHP.  
  - Indentation: 4 spaces, no tabs.
  - Curly braces always on a new line for classes and methods.

- Write small, single-responsibility functions.

- Add type hints and return types whenever possible.

- Use comments to explain complex logic — avoid redundant comments.

- Write unit tests for critical functionalities.

- Remove unused code and dead files regularly.

---

## **Git Best Practices**

- Always create a new branch for each feature, fix, or improvement.  
  ✅ Example: `feature/add-3d-planning-module` or `bugfix/fix-upload-error`.

- Commit often with clear, descriptive messages:  
  ✅ Example: `Fix patient scan upload timeout error`

- Sync your branch with `main` or `develop` regularly to avoid large conflicts.

- Use Pull Requests (PRs) for every merge into the main branch — no direct pushes.

- Ask at least one team member for code review before merging.

- Squash commits if appropriate to keep history clean.

---

## **Git Rules**

- **Branch Naming**  
  - `feature/` for new features.  
  - `bugfix/` for bug fixes.  
  - `hotfix/` for urgent production issues.  
  - `chore/` for refactoring or maintenance tasks.

- **Commit Message Format**  
  - Use the present tense: *Add*, *Fix*, *Update*.
  - Keep the first line under 50 characters.
  - Optionally add a detailed description below if needed.

- **Merge Rules**  
  - Only merge when the CI/CD pipeline passes.
  - Avoid force pushes on shared branches.

- **Tagging Releases**  
  - Use semantic versioning: `v1.2.0`.

---

## **Learn Git**

Here are some helpful links and commands to get started or refresh your Git skills:

- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
- [Git Handbook by GitHub](https://guides.github.com/introduction/git-handbook/)

**Common commands:**

```bash
git status           # Check changes
git checkout -b my-branch   # Create and switch to new branch
git add .            # Stage all changes
git commit -m "Add new feature"
git pull origin main # Get latest changes from main
git push origin my-branch   # Push changes
````

---

## **Contact**

If you have questions, suggestions, or improvements, feel free to open a discussion or reach out to the project maintainers.

