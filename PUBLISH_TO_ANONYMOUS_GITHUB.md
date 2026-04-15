# Publish This Copy To Anonymous GitHub

This environment can prepare the anonymous repository locally, but it cannot create a truly anonymous remote GitHub repository because the only connected GitHub account here is the real account `huiyang-yi`.

Recommended steps:

1. Sign in to the anonymous GitHub account that should own the review repository.
2. Create a new **private** repository there.
3. Do **not** create it as a fork.
4. Leave README, `.gitignore`, and license initialization disabled so the repository starts empty.

Push commands from this local copy:

```bash
cd /tmp/CausalCompass-anonymous
git remote add origin git@github.com:<anonymous-account>/<anonymous-repo>.git
git push -u origin main
```

GitHub settings to verify before sharing:

- Repository owner is the anonymous account.
- Description, website, and topics do not mention the original project page, arXiv page, or author identity.
- GitHub Pages is disabled unless you later publish an anonymous documentation site.
- No releases, tags, or Actions secrets reveal author identity.
