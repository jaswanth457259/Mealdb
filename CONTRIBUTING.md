# Team Development Rules

## 1. Never Push Directly to Main
- The main branch must always remain stable.
- No one should push directly to main.
- All changes must go through Pull Requests.

## 2. Main Branch Must Always Work
- The project in main must run without errors.
- Do not merge incomplete features.
- Main is production-ready code.

## 3. Work in Feature Branches
- Every developer must create their own branch.
- Branch name format:
  feature-name
  bugfix-name

Example:
feature-login
feature-cart

## 4. Pull Latest Code First

Before starting work run:

git checkout main
git pull origin main

Then create a branch.

## 5. One Feature = One Pull Request

Each Pull Request must contain only one feature.

Example:
✔ Login feature PR
✔ Cart feature PR

Not:

❌ Login + Cart together

## 6. Code Review Required

At least one team member must approve before merging.

Do not merge your own PR.

## 7. Write Clear Commit Messages

Good Examples:

Added login validation
Fixed cart calculation bug

Bad Examples:

update
final
done

## 8. No Sensitive Files

Never upload:

- Passwords
- API Keys
- Database configs

Use:

.env file

## 9. Delete Branch After Merge

After merging:

Delete the branch.

## 10. Communicate Major Changes

Discuss before:

- Changing database
- Changing backend structure
- Changing frontend framework
