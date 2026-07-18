<div align="center">
  <h1>giscus · lailai.one</h1>
  <p>English | <a href="README.zh-Hans.md">简体中文</a></p>
  <p>
    <img src="https://img.shields.io/github/last-commit/lailai0916/giscus?style=flat-square" alt="last commit" />
    <img src="https://img.shields.io/github/license/lailai0916/giscus?style=flat-square" alt="license" />
  </p>
</div>

The GitHub Discussions backend used by [lailai.one](https://lailai.one) for article
comments through [giscus](https://giscus.app).

## Purpose

💬 **Comment storage** — giscus maps website pages to GitHub Discussions in this
repository.

🔐 **GitHub identity** — readers authenticate with GitHub; this repository stores no
application passwords or custom account database.

🧹 **No application code** — website source and giscus integration settings belong in
the website repository. This repository exists for discussion data and moderation.

## Moderation

Use the repository's **Discussions** tab to review, answer, lock, or remove comments.
Issues are reserved for repository-level configuration problems, not article replies.

## License

Repository-authored files are licensed under the [MIT License](LICENSE). User-generated
Discussions and comments remain the work of their respective authors and are not
relicensed by this repository.
