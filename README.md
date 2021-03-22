# `ja-space-between-half-and-full-width` is not enabled

```
~/workspaces/test-textlint-rule-preset-ja-spacing main*
❯ textlint -c .textlintrc 1.md
```

# `ja-space-between-half-and-full-width` is enabled

```
~/workspaces/test-textlint-rule-preset-ja-spacing main*
❯ textlint -c .textlintrc-1 1.md

/Users/kyanny/workspaces/test-textlint-rule-preset-ja-spacing/1.md
  1:3  ✓ error  原則として、全角文字と半角文字の間にスペースを入れます。  ja-spacing/ja-space-between-half-and-full-width
  1:7  ✓ error  原則として、全角文字と半角文字の間にスペースを入れます。  ja-spacing/ja-space-between-half-and-full-width

✖ 2 problems (2 errors, 0 warnings)
✓ 2 fixable problems.
Try to run: $ textlint --fix [file]
```

---

```
❯ textlint --version
v11.9.0
```
