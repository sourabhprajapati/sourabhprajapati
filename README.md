<h1 align="center">Hi, I'm Sourabh Prajapati 👋</h1>

<h3 align="center">Full-Stack & Mobile Developer • React, React Native, Next.js, FastAPI • AWS & CI/CD</h3>

---

### 🚀 About Me

- 🏫 I build **education technology products** used daily by schools: web portals, mobile apps and the pipelines that ship them
- 🧩 5+ years in tech. I take features from **database schema to production**, including app store releases
- 🔁 Alongside my own work, I **review pull requests and run production releases** for our development team
- ☁️ Hands-on with **AWS, Docker, Terraform and Kubernetes**, and always sharpening my DevOps skills
- 💼 Available for **freelance and contract work**: React Native releases, full-stack features and AWS deployments

---

### 💻 Production Work

**Olympiad registration portal** · *lead developer* · FastAPI, React, PostgreSQL, Docker, AWS<br>
Registration, seat allocation and admit cards for an inter-school olympiad, replacing manual spreadsheets. I wrote most of the codebase: admin and school workspaces with strict role isolation, bulk Excel import with validation and duplicate detection, deterministic roll numbers, a three-step verify-and-lock flow, HMAC-signed login links, an admit card designer with signature capture and Word export, and a bilingual English/Hindi interface. SQLite locally, PostgreSQL in production, Dockerized and deployed to AWS.

**School ERP mobile app** · React Native, iOS and Android<br>
Companion app bringing fees, attendance, homework, results and timetables to parents, students and teachers. Includes charts, PDF marksheets, Excel export and offline storage. The server encrypts every API response and React Native has no Web Crypto, so I wrote a decryption layer that patches fetch and axios globally instead of changing hundreds of call sites. I also own the release pipeline: Codemagic and EAS builds, keystore signing, App Store Connect and TestFlight.

**Reels feature for a student talent app** · React Native<br>
Vertical video feed with correct seek and playback handling, share and report sheets, search, public profiles and the full auth flow. Plus a GitHub Actions and fastlane pipeline that ships iOS builds to TestFlight.

**Video review platform** · Next.js, Prisma, PostgreSQL, AWS S3<br>
Back office where student video submissions move through evaluator, reviewer and moderator stages. Prisma schema and migrations, follow and password-reset APIs, and a fix for ffmpeg thumbnail failures on videos with non-standard H.264 colour ranges.

---

### 🤝 Team Projects I Contributed To

**Multi-tenant school ERP** · React, Node.js, Express, MongoDB<br>
School management platform used daily by staff, students and parents: admissions, fees with concessions and late fees, attendance, exams, result cards, timetables, transport, ID and admit cards, and SMS credits, across 95 REST modules with AES-256 encrypted API responses. My work: role-based permission guards, paid-fee processing, the activity calendar, and the integration with our question-paper generator.

**AI answer-sheet checker** · Python, FastAPI, Celery, Redis, PostgreSQL, S3<br>
Automatically grades scanned handwritten early-years exam sheets, with around 20 question-type evaluators built on Google Vision and Gemini, and a reconciler that re-drives stuck sheets. My work: the production cutover to AWS, including server deploy scripts and fixes for S3 configuration and for storage being wiped on redeploy.

**AI question-paper generator** · Python, FastAPI, LlamaIndex, Pinecone, Gemini<br>
Generates exam papers strictly from the textbook series a school owns, using retrieval over indexed PDFs, with PDF and editable Word export including Hindi and Sanskrit Devanagari. My work: API changes and font rendering fixes in the PDF pipeline.

<sub>All production and team projects were built for my employer, so their code is private.</sub>

---

### ⚙️ DevOps Projects

**[EasyShop](https://github.com/sourabhprajapati/EasyShop)** · E-commerce app on AWS EKS<br>
End-to-end deployment of an open-source training project. Terraform provisions the VPC, EKS cluster and Jenkins server. A Jenkins pipeline builds Docker images, runs tests, scans with Trivy and updates the Kubernetes manifests. The cluster runs a MongoDB StatefulSet, autoscaling and HTTPS ingress with cert-manager. I also fixed the pipeline's disk exhaustion and oversized builds.

**[Wanderlog](https://github.com/sourabhprajapati/Wanderlog)** · DevSecOps CI/CD pipeline<br>
Worked through a security-focused pipeline for an open-source travel blog app: Jenkins with Trivy, OWASP and SonarQube quality gates, Docker builds and Terraform-provisioned AWS infrastructure.

**[Cloud-Native Microservices Platform](https://github.com/sourabhprajapati/cloudnative-microservices-platform)** · Kubernetes reference system<br>
Forked the OpenTelemetry demo to study a polyglot microservices system on Kubernetes: Kafka messaging, gRPC between services, and observability with OpenTelemetry, Prometheus, Grafana and Jaeger.

---


---

### 🛠️ Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,nodejs,express,python,fastapi,postgres,mongodb,prisma,tailwind,docker,aws,githubactions,terraform,kubernetes,jenkins,git,linux" alt="tech stack" />
</p>

**Frontend:** React · Next.js · TypeScript · Tailwind<br>
**Mobile:** React Native · EAS · Codemagic · fastlane · TestFlight · Google Play Console<br>
**Backend:** Node.js · Express · Python · FastAPI<br>
**Data:** PostgreSQL · Prisma · MongoDB · SQLite<br>
**Cloud & DevOps:** AWS (EC2, ECS, S3, EKS) · Docker · GitHub Actions · Terraform · Kubernetes · Jenkins · PM2

---

### 🌐 Connect With Me

<p align="left">
  <a href="https://www.linkedin.com/in/sourabh-prajapati-43b467189/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a>
  <a href="mailto:sourabhprajapati920@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
</p>
