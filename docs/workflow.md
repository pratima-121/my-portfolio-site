# Development Workflow

## Branching Strategy

- main → production-ready code
- feature/* → new changes

## Workflow Steps

1. Create a branch
    git checkout -b feature/about-page


2. Make changes

3. Check status

git status

4. Add changes

git add .

5. Commit

git commit -m "Update about page"

6. Push branch

git push origin feature/about-page


7. Create Pull Request (PR) in GitHub

8. Merge PR into main

9. Delete branch

---

## Rules

- Never commit directly to main
- One branch = one change
- Using meaningful branch names
- Using clear commit messages