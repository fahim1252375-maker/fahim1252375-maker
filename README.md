<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,55:1D4ED8,100:0F766E&height=190&section=header&text=Fahim&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Development%20%7C%20Software%20Engineering&descAlignY=60&descSize=16" alt="Fahim — Software Development" />
</p>

<h1 align="center">Hi, I'm Fahim 👋</h1>
<p align="center">
  <strong>Aspiring Full-Stack Developer | React · JavaScript · Node.js · TypeScript · MongoDB</strong><br />
  HSC Science Student · Sylhet, Bangladesh
</p>

<p align="center">
  <a href="https://grand-starlight-0c4115.netlify.app"><img src="https://img.shields.io/badge/Portfolio-Visit%20Website-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio Website" /></a>
  <a href="https://www.linkedin.com/in/md-minhazur-rahman-fahim-469b03447/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:fahim1252375@icloud.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/fahim1252375-maker?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Explore%20Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore GitHub repositories" /></a>
</p>

---

## About

I'm **MD. Minhazur Rahman Fahim**, a science student from Bangladesh developing practical software engineering skills through hands-on projects. I enjoy building responsive web experiences and learning how to make applications more reliable, secure, and maintainable.

- 🎓 HSC Science student at **Blue Bird High School & College**
- 📍 Sylhet, Bangladesh
- 💻 Focused on full-stack web development and backend fundamentals
- 🤖 Exploring practical AI applications and automation
- 🧪 Learning through implementation, testing, code review, and iteration

## Technical Skills

| Area | Technologies |
|---|---|
| Frontend | HTML5, CSS3, JavaScript, React, Bootstrap, Tailwind CSS, Vite |
| Backend | Node.js, Express.js, TypeScript, REST APIs |
| Database & Authentication | MongoDB, Mongoose, JWT, bcryptjs |
| Programming & Learning | Python, C++, machine-learning fundamentals |
| Tools | Git, GitHub, Figma, Postman, Microsoft 365 |

## Selected Projects

### FloodGuard AI — Flood & Health Preparedness Prototype

A bilingual decision-support prototype focused on flood preparedness and health-response planning in the Sylhet–Sunamganj region of Bangladesh.

- Combines weather context, modelled hydrological inputs, transparent risk indicators, family safety planning, shelter-readiness workflows, and community-report moderation.
- Separates operational API data, derived indicators, and simulated examples in the interface and documentation.
- Explicitly documents that it is a research/demo prototype—not an official warning service, clinically validated disease forecast, or guaranteed safe-route system.
- **Source and technical documentation:** [floodguard-ai](https://github.com/fahim1252375-maker/floodguard-ai)

### ShasthoNote AI — Bangla-English Health Information Workspace

A health-information organization prototype for preparing for clinical conversations.

- Organizes consultation notes, documents, appointments, self-recorded measurements, and learning materials.
- Uses AI-assisted summaries and explanations while stating that the application is not a diagnostic or treatment system.
- Documents synthetic demo data, privacy boundaries, CI checks, and limitations of integration testing.
- **Source and technical documentation:** [shasthonote-ai](https://github.com/fahim1252375-maker/shasthonote-ai)

### BlogSpace — Full-Stack Blogging Application

A full-stack blogging application combining a browser-based interface, Node.js/Express API, and MongoDB persistence.

- JWT-based authentication and password hashing with bcryptjs
- Protected author dashboard and create, edit, and delete post workflows
- Server-side author-ownership checks for post updates and deletion
- Authentication rate limits, reduced health-endpoint information exposure, trusted-proxy configuration, and baseline HTTP security headers
- TypeScript validation, automated tests, and production build checks
- **Security milestone:** [Pull Request #2 — merged](https://github.com/fahim1252375-maker/blogspace-fullstack/pull/2)
- **Source:** [blogspace-fullstack](https://github.com/fahim1252375-maker/blogspace-fullstack)

### BlogSpace — Frontend Application

A responsive multi-page blogging interface with article search, category filters, reader modal, authentication screens, and an author dashboard.

- Built with HTML, CSS, vanilla JavaScript, and Vite
- Uses LocalStorage for browser-only demonstration data
- **Live demo:** [Open BlogSpace](https://bejewelled-haupia-dd6200.netlify.app)
- **Source:** [blog-application-frontend](https://github.com/fahim1252375-maker/blog-application-frontend)

### Cinnamon Restaurant — Website Concept

A responsive restaurant website concept with an interactive menu, gallery, mobile navigation, and WhatsApp reservation-request handoff.

- Built with semantic HTML, CSS, and vanilla JavaScript
- The WhatsApp handoff prepares a request; it does not confirm or store bookings
- **Source:** [restaurant-website-frontend](https://github.com/fahim1252375-maker/restaurant-website-frontend)


## Open Source Contributions

I contribute to established open-source projects by investigating reported issues, writing focused fixes, and adding regression tests.

### Neo.mjs — Open-source JavaScript Framework

- **Merged — [PR #20785: Fix UUID generation on insecure HTTP origins](https://github.com/neomjs/neo/pull/20785)**  
  Added a shared RFC 4122 v4 UUID utility based on `crypto.getRandomValues()`, migrated browser-side call sites away from `crypto.randomUUID()`, preserved the existing `CanvasGroups.mint()` ID format, and added regression coverage for insecure HTTP origins. The pull request changed 13 files; the reviewer recorded all 7 required CI checks as green. The PR description notes that local tests were not run, so the verification claim is specifically about CI.

- **Merged — [PR #20746: Enhance download tests and document BlobPart functionality](https://github.com/neomjs/neo/pull/20746)**  
  Clarified the `FileDownload#saveText` API documentation for text and binary `BlobPart` payloads and added focused Playwright unit tests for string and `Uint8Array` downloads. The targeted local test run passed (2 tests).

- **Merged — [PR #20746: Enhance download tests and document BlobPart functionality](https://github.com/neomjs/neo/pull/20746)**  
  Clarified the `FileDownload#saveText` API documentation for text and binary `BlobPart` payloads and added focused Playwright unit tests for string and `Uint8Array` downloads. The targeted local test run passed (2 tests).

- **Merged — [PR #20785: Fix UUID generation on insecure HTTP origins](https://github.com/neomjs/neo/pull/20785)**  
  Resolved [issue #20765](https://github.com/neomjs/neo/issues/20765). Added a shared RFC 4122 v4 UUID utility using `crypto.getRandomValues()`, replaced browser-side `crypto.randomUUID()` usage across 18 call sites, and updated `CanvasGroups.mint()` while preserving its existing 32-character hexadecimal ID format. Added unit coverage and a Playwright component regression test for non-localhost plain-HTTP origins.  
  **Change size:** 13 files, 119 additions, 26 deletions; 3 commits.  
  **Verification:** The reviewer recorded all 7 required CI checks as green. GitHub workflow runs for unit/component tests, all 14 E2E engine shards, build, consumer runtime build, CodeQL, and file-size guard completed successfully. The PR description transparently notes that local tests were not run; CI provided the verification.

Both pull requests were merged into the project's `dev` branch. AI-assisted development was disclosed in the originating #20736 issue discussion and in the #20785 PR description. I am responsible for reviewing and maintaining the contributions I submit.

### Microsoft — ML-For-Beginners

- **Open — [PR #1082: Migrate Gym examples to Gymnasium](https://github.com/microsoft/ML-For-Beginners/pull/1082)**  
  Updated the reinforcement-learning lesson materials to use Gymnasium APIs, including the `terminated`/`truncated` step results. The pull request is open and awaiting maintainer review as of November 13, 2026; it is not presented as merged or approved.


## Application Evidence Index

For a concise, status-labelled index of selected projects, merged upstream contributions, work under review, and evidence limitations, see [APPLICATION_EVIDENCE.md](./APPLICATION_EVIDENCE.md).

## Engineering Practice

Recent BlogSpace work has helped me practise engineering beyond interface development:

- **Authentication security:** per-IP registration and login rate limits.
- **Safer operational responses:** reduced database configuration details exposed by the public health endpoint.
- **Proxy-aware request handling:** configurable trusted-proxy handling for client-IP detection.
- **HTTP security fundamentals:** baseline Referrer-Policy and Permissions-Policy headers.
- **Quality checks:** TypeScript validation, automated tests, production builds, and pull-request workflows.
- **Version control:** dedicated feature branches and a merged security pull request.

[Review the BlogSpace security changes](https://github.com/fahim1252375-maker/blogspace-fullstack/pull/2)

## Learning & Recognition

- **Certificate of Excellence — Full Stack Development with MERN**, Grameenphone Academy × CodersTrust (October 2026)
- **Best Project / Best Performer recognition**, IT Aid Web Design Course
- Microsoft Learn technical learning badges
- Studying machine-learning concepts through a personal [study fork of Microsoft's ML-For-Beginners curriculum](https://github.com/fahim1252375-maker/ML-For-Beginners)
- Model United Nations, debate, STEM learning, and community volunteering

## Collaboration

I'm interested in thoughtful collaboration on beginner-friendly open-source work, frontend and full-stack applications, API development, and practical AI automation. I value clear communication, useful feedback, and code that can be understood and maintained.

For a project discussion, contact me through [LinkedIn](https://www.linkedin.com/in/md-minhazur-rahman-fahim-469b03447/) or [email](mailto:fahim1252375@icloud.com), or open an issue in the relevant repository.

## Current Focus

- Strengthening React, JavaScript, TypeScript, and Node.js foundations
- Improving API design, authentication, authorization, and database integration
- Writing meaningful tests and applying safer development practices
- Learning Python, machine learning, and practical AI automation

## AI Use & Development Transparency

I may use AI tools as supporting aids for brainstorming, understanding unfamiliar concepts, debugging, and drafting documentation. AI is not a substitute for my own learning or review: I am responsible for understanding, adapting, and testing the work I publish. I do not treat AI-generated suggestions as verified results until I check them against the code and relevant tests. Where relevant, AI assistance is disclosed in project documentation, and I aim to describe my own contributions and project capabilities accurately.

## Connect

- **Portfolio:** [Visit my personal portfolio](https://grand-starlight-0c4115.netlify.app)
- **LinkedIn:** [MD. Minhazur Rahman Fahim](https://www.linkedin.com/in/md-minhazur-rahman-fahim-469b03447/)
- **Email:** [fahim1252375@icloud.com](mailto:fahim1252375@icloud.com)
- **GitHub:** [@fahim1252375-maker](https://github.com/fahim1252375-maker)

---

<p align="center"><em>Build with purpose. Test with care. Improve with every iteration.</em></p>
