git add .
git commit -m "feat: initial gift card platform release"
git tag -a v1.0.0 -m "Release v1.0.0"
git push origin HEAD
git push origin v1.0.0
gh release create v1.0.0 --title "v1.0.0" --notes-file release-notes.md