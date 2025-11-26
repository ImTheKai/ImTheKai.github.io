# This repo is primarily for hosting my presentations

Pull a new subtree into this master branch and subfolder exampel:

```
git subtree add --prefix it-tage-2025 slides-repo it-tage-frankfurt-2025 --squash
```

If you want to update your local state, after remote changes, use `pull` instead

```
git subtree pull --prefix it-tage-2025 slides-repo it-tage-frankfurt-2025 --squash
```
