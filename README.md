## Commit Message Convention

This website follows [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

Commit message akan dicek menggunakan [husky and commit lint](https://theodorusclarence.com/library/husky-commitlint-prettier), jika convention salah, maka tidak bisa melakukan commit

### Format

`<type>(optional scope): <description>`
Contoh: `feat(pre-event): add speakers section`

### 1. Type

Type yang bisa digunakan adalah:

- feat → Jika ada penambahan/pengurangan fitur codingan. Contoh: `feat: add table on landing page`, `feat: remove table from landing page`
- fix → Jika ada bug fixing, diikuti dengan bugnya. Contoh: `fix: illustration overflows in mobile view`
- BREAKING CHANGE → Jika ada perubahan yang signifikan. Contoh: `BREAKING CHANGE: change login flow to not save token in localStorage`
- docs → Update documentation (README.md)
- style → Update style, tidak mengubah logic sama sekali (reorder import, fix whitespace, remove comment)
- chore → Jika menginstall, mengupdate dependecies
- refactor → Jika ada perubahan code, dengan end result yang sama, tetapi approach berbeda yang lebih baik.
- ci → Update github workflows, husky
- test → Update testing suite
- perf → Fix sesuatu yang bersifat improve performance (derived state, memo)
- vercel → Jika ada commit kosong untuk trigger vercel deployment. Contoh: `vercel: trigger deployment`

### 2. Optional Scope

Contoh labeling per page `feat(pre-event): add date label`

\*Jika tidak ada scope, maka tidak perlu ditulis.

Scope yang bisa digunakan:
