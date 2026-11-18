# GitHub-қа жүктеу нұсқаулығы

1. GitHub-та `habit-tracker-mobile` деген **Public** бос репозиторий ашыңыз (README қоспаңыз).
2. Description: `Mobile application for building and tracking healthy habits`
3. Topics: `android`, `habit-tracker`, `uml`, `mobile-app`, `java`
4. Осы ZIP-ті шығарып, `habit-tracker-mobile` папкасында Git Bash ашыңыз.
5. Төмендегі командаларды **жеке-жеке** орындаңыз (GitHub логинін өзгертіңіз):

```bash
git init
git branch -M main
git add README.md .gitignore
git commit -m "Add project README and gitignore"
git remote add origin https://github.com/YOUR_USERNAME/habit-tracker-mobile.git
git push -u origin main
git switch -c behavior-diagrams
git add docs/analysis/activity-add-habit.drawio docs/analysis/activity-add-habit.png
git commit -m "Add activity diagram for habit creation"
git add docs/analysis/sequence-add-habit.drawio docs/analysis/sequence-add-habit.png
git commit -m "Add sequence diagram for habit creation"
git add GITHUB_STEPS.md
git commit -m "Document GitHub workflow and diagram files"
git push -u origin behavior-diagrams
```

6. GitHub-та **Compare & pull request** → base `main`, compare `behavior-diagrams` → **Create pull request** → **Merge pull request** → **Confirm merge**.
7. Git Bash-та `git switch main` және `git pull origin main` орындаңыз.
8. README-дегі PNG сілтемелерін тексеріңіз. GitHub репозиторийінің сілтемесін мұғалімге жіберіңіз.

Ескерту: ZIP файлындағы Git commit тарихы алдын ала жасалмаған; командаларды өз компьютеріңізде орындаңыз.
