<div align="center">
  <!-- Custom Logo -->
  <img src="public/assets/icons/logo.svg" alt="SnapCast Logo" width="120" />

  <h1 align="center">SnapCast</h1>
  <p align="center">
    <em>Effortless Screen Recording & Instant Sharing.</em><br />
    Built with Next.js, Better Auth, Bunny CDN, and a whole lot of love.
  </p>

  <!-- Demo Button -->
  <a href="https://screen-recording-and-sharing-app.onrender.com/">
    <img src="https://img.shields.io/badge/View_Demo-0ea5e9?style=for-the-badge&logo=rocket&logoColor=white" alt="View Demo"/>
  </a>
</div>

---

<div align="center">
  <!-- Badges -->
  <img src="https://img.shields.io/github/stars/Ansh701/capto?style=for-the-badge&color=0ea5e9&logo=github" alt="Stars Badge"/>
  <img src="https://img.shields.io/github/forks/Ansh701/capto?style=for-the-badge&color=0ea5e9" alt="Forks Badge"/>
  <img src="https://img.shields.io/github/issues/Ansh701/capto?style=for-the-badge&color=0ea5e9" alt="Issues Badge"/>
</div>

---

### 🚀 Key Features

| Feature                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| 🎥 Instant Screen Recording | Record screen, window, or tab directly from the browser—no downloads needed |
| 🔐 Secure Authentication   | Google login via Better Auth for seamless access                          |
| ☁️ Cloud Video Uploads     | Fast uploads to Bunny CDN for reliable streaming                          |
| 👁️ Public & Private Videos | Toggle visibility for each video with ease                                |
| 🔍 Dynamic Filtering       | Search and filter your video library instantly                            |
| 🖼️ Auto Thumbnails         | Beautiful thumbnails generated automatically                              |
| 📱 Responsive Design       | Works perfectly across all devices                                        |

---

### 🏁 Getting Started

<details>
<summary><strong>Prerequisites</strong></summary>

- [Node.js](https://nodejs.org/en/) v18+
- [pnpm](https://pnpm.io/) or npm/yarn
- [Git](https://git-scm.com/)
</details>

<details>
<summary><strong>Installation</strong></summary>

git clone https://github.com/Ansh701/capto.git
cd capto
pnpm install
pnpm db:push
pnpm dev


Your app will be live at `http://localhost:3000`
</details>

<details>
<summary><strong>Environment Variables</strong></summary>

Create a `.env` file and add:

NEXT_PUBLIC_BASE_URL=http://localhost:3000
BETTER_AUTH_URL=http://localhost:3000
BETTER_AUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

XATA_API_KEY=
DATABASE_URL_POSTGRES=
DATABASE_URL=

BUNNY_STORAGE_ACCESS_KEY=
BUNNY_LIBRARY_ID=
BUNNY_STREAM_ACCESS_KEY=

ARCJET_API_KEY=

For deployment, update URLs to your production domain (e.g., https://screen-recording-and-sharing-app.onrender.com) in both `.env` and Google Cloud Console.
</details>

---

### 🤝 Contributing

We welcome contributions! Fork the repo, create a feature branch, and submit a PR. Or open an issue with the tag `enhancement`.

git checkout -b feature/AmazingFeature
git commit -m "Add some AmazingFeature"
git push origin feature/AmazingFeature


---

<div align="center">
  <h3>Made with ❤️ by <a href="https://github.com/Ansh701">Ansh Upadhyay</a></h3>
  <a href="https://github.com/Ansh701">GitHub</a> ·
  <a href="https://x.com/AnshUpadhy77416">Twitter</a> ·
  <a href="https://www.linkedin.com/in/ansh0">LinkedIn</a>
</div>
