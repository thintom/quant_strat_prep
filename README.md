1. Environment Initialization
- Terminal: Use Git Bash (Windows) for a Unix-like experience.
- Global Identity: Link your commits to your professional profile:

git config --global user.name "Your Real Name"
git config --global user.email "your_github_email@example.com"


2. Local Repository Creation
- Directory Management: Create a dedicated workspace (e.g., in Documents):

mkdir Quant-Strat-Preparation
cd Quant-Strat-Preparation
git init


- Safety Net: Create a .gitignore to prevent pushing "junk" files (like .ipynb_checkpoints/) to the cloud:

touch .gitignore


3. Connecting to the Cloud (GitHub)
- The Remote Link: Create a repository on GitHub.com first, then link it to your local folder:

git remote add origin https://github.com
git branch -M main


4. The Daily Workflow
- Stage Changes: git add . (Gather your new code).
- Commit Logic: git commit -m "feat: [topic] [specific problem solved]" (Explain what you built).
- Push to Production: git push (Upload to GitHub).

Example

touch README.md
git add README.md
git commit -m "docs: add repository infrastructure tutorial"
git push