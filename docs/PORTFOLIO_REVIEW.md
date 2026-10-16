# Portfolio maintenance verification

Reviewed 2026-10-16. All 13 project repositories were updated on main. Existing history was retained; the seven archive imports have original snapshots and SHA-256 manifests.

| Repository | Files on GitHub | Verified commit | GitHub checks |
| --- | ---: | --- | --- |
| [Avada-Layout](https://github.com/hesamafk/Avada-Layout) | 78 | [0f165fb](https://github.com/hesamafk/Avada-Layout/commit/0f165fb0fdd44a48a8b9042020390507875bb311) | [Passed](https://github.com/hesamafk/Avada-Layout/actions/runs/38870417422) |
| [SmartDocs-AI](https://github.com/hesamafk/SmartDocs-AI) | 24 | [8bdd43b](https://github.com/hesamafk/SmartDocs-AI/commit/8bdd43ba049b06062b2b7799ef3e1a012c988767) | [Passed](https://github.com/hesamafk/SmartDocs-AI/actions/runs/38870416561) |
| [Bimeh-Website](https://github.com/hesamafk/Bimeh-Website) | 19 | [00bc519](https://github.com/hesamafk/Bimeh-Website/commit/00bc5199797f9a631f4fb2f3c0d94dec42f33ba4) | [Passed](https://github.com/hesamafk/Bimeh-Website/actions/runs/38870432899) |
| [Enfold-Layout](https://github.com/hesamafk/Enfold-Layout) | 77 | [59f4722](https://github.com/hesamafk/Enfold-Layout/commit/59f4722117aed6e34402854a14fbd79b63ecb776) | [Passed](https://github.com/hesamafk/Enfold-Layout/actions/runs/38870408263) |
| [University-Website](https://github.com/hesamafk/University-Website) | 12 | [28af3cd](https://github.com/hesamafk/University-Website/commit/28af3cda691a38a605a7174340fd7330bbb7ba50) | [Passed](https://github.com/hesamafk/University-Website/actions/runs/38870426180) |
| [CS50-SongApp](https://github.com/hesamafk/CS50-SongApp) | 22 | [9439b94](https://github.com/hesamafk/CS50-SongApp/commit/9439b94a564c040720102b37e663420a6ae97b71) | [Passed](https://github.com/hesamafk/CS50-SongApp/actions/runs/38870423760) |
| [Login-Form](https://github.com/hesamafk/Login-Form) | 12 | [4689ace](https://github.com/hesamafk/Login-Form/commit/4689ace468e75efc09dd93229e557728a65e2b06) | [Passed](https://github.com/hesamafk/Login-Form/actions/runs/38870406553) |
| [Vpn_Store](https://github.com/hesamafk/Vpn_Store) | 25 | [4a7e02e](https://github.com/hesamafk/Vpn_Store/commit/4a7e02e4fcee0523e4c0d0be37d6fd17b758e604) | [Passed](https://github.com/hesamafk/Vpn_Store/actions/runs/38870436472) |
| [Wine_Shop](https://github.com/hesamafk/Wine_Shop) | 10 | [c78bc1e](https://github.com/hesamafk/Wine_Shop/commit/c78bc1e66d60b32973c2fd052ea3172997c49da8) | [Passed](https://github.com/hesamafk/Wine_Shop/actions/runs/38870432194) |
| [Art_Blog](https://github.com/hesamafk/Art_Blog) | 10 | [007e71b](https://github.com/hesamafk/Art_Blog/commit/007e71bb76ff9c5700b558b6ff9c14787525da3c) | [Passed](https://github.com/hesamafk/Art_Blog/actions/runs/38870421047) |
| [AI-Code-Mentor](https://github.com/hesamafk/AI-Code-Mentor) | 31 | [53f8980](https://github.com/hesamafk/AI-Code-Mentor/commit/53f8980761c085f52e0d592b163e985d75b272bd) | [Passed](https://github.com/hesamafk/AI-Code-Mentor/actions/runs/38870411096) |
| [HesamBlog](https://github.com/hesamafk/HesamBlog) | 18 | [9451331](https://github.com/hesamafk/HesamBlog/commit/9451331b167c846bd6886b42f14dd23370df6507) | [Passed](https://github.com/hesamafk/HesamBlog/actions/runs/38870434957) |
| [Beauty](https://github.com/hesamafk/Beauty) | 28 | [f94420b](https://github.com/hesamafk/Beauty/commit/f94420b08614422284a492163c2c0ce214697730) | [Passed](https://github.com/hesamafk/Beauty/actions/runs/38870419973) |

Every final local file path and Git blob SHA matched its repository tree. Previously committed files and the original mentor archive were retained. No force push was used.

## Validation performed

- Rendered 12 interfaces at 1280 px and 390 px. Verified JavaScript errors, horizontal overflow and loaded images; inspected desktop/mobile screenshots.
- Browser walkthroughs: login UI, portfolio menu/contact form, insurance rating/admin/home flow, blog search, validated beauty-cart restore, and both AI apps using mocked request/stream responses.
- Four Flask/SQLite integration tests and four RAG/stream helper tests passed.
- Both React apps installed from lockfiles and built successfully.
- GitHub Actions passed for every project, including real PHP syntax and MySQL schema/prepared-query/transaction checks for the store.

## Profile

A public profile README links every project. The bio and repository descriptions were updated; six projects were pinned. A screenshot of the resulting profile is retained in profile-preview.jpg.

## Practical limits

These remain local portfolio projects. No public deployment, live paid AI request, real payment, email delivery or exhaustive cross-browser certification was performed. Browser-storage demos do not provide shared server databases. Exact setup and remaining limitations are documented in each project's README and docs/VALIDATION.md. Passing these checks is not a guarantee of zero defects.
