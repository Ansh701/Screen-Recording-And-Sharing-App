<div align="center">
<br />
<br />
<!-- Logo -->
<img src="https://raw.githubusercontent.com/user-attachments/assets/5a9e3a7a-3b5e-4e4f-8b2a-7c6f1a8c8e8a" alt="Capto Logo" width="120" />
<h1 align="center">Capto</h1>
<p align="center">
Effortless Screen Recording & Instant Sharing.
<br />
Built with Next.js, Better Auth, and a whole lot of love.
<br />
<br />
<a href="https://screen-recording-and-sharing-app.onrender.com/">
<img src="https://img.shields.io/badge/View_Demo-0ea5e9?style=for-the-badge&logo=rocket&logoColor=white" alt="View Demo"/>
</a>
<br />
<br />
<a href="#-key-features"><strong>Key Features</strong></a>
·
<a href="#-getting-started"><strong>Getting Started</strong></a>
·
<a href="#-contributing"><strong>Contributing</strong></a>
</p>
</div>
<!-- Badges -->
<div align="center">
<img src="https://img.shields.io/github/license/your-username/capto?style=for-the-badge&color=0ea5e9" alt="License Badge"/>
<img src="https://img.shields.io/github/stars/your-username/capto?style=for-the-badge&color=0ea5e9&logo=github" alt="Stars Badge"/>
<img src="https://img.shields.io/github/forks/your-username/capto?style=for-the-badge&color=0ea5e9" alt="Forks Badge"/>
<img src="https://img.shields.io/github/issues/your-username/capto?style=for-the-badge&color=0ea5e9" alt="Issues Badge"/>
</div>
🚀 Key Features
A suite of powerful features designed for a seamless user experience.
Feature
Description
Icon
Instant Screen Recording
High-quality screen, window, or tab recording directly from the browser. No downloads required.
🎥
Secure Authentication
Robust and secure user authentication powered by better-auth, including Google social login.
🔐
Cloud Video Uploads
Automatic and fast video uploads to Bunny CDN for reliable storage and streaming.
☁️
Public & Private Videos
Control who sees your content with simple visibility toggles for each video.
👁️
Dynamic Filtering & Search
Easily find any video with a powerful search and filtering system.
🔍
Auto-Generated Thumbnails
Thumbnails are automatically created for every uploaded video, making your library look great.
🖼️
Responsive Design
A beautiful and fully responsive interface that works perfectly on any device.
📱

🏁 Getting Started
Ready to run Capto locally? Here’s how you can do it.
<details>
<summary><strong>Prerequisites</strong></summary>
<br />
Before you begin, ensure you have the following installed:
<ul>
<li><a href="https://nodejs.org/en/">Node.js</a> (v18 or higher)</li>
<li><a href="https://pnpm.io/">pnpm</a> (or npm/yarn)</li>
<li><a href="https://git-scm.com/">Git</a></li>
</ul>
</details>
<details>
<summary><strong>Installation & Setup</strong></summary>
<br />
Clone the repository:
git clone https://github.com/your-username/capto.git
cd capto


Install dependencies:
pnpm install


Set up environment variables:
Create a .env file in the root of your project and add the necessary variables. See the section below for a full list.
Push the database schema:
This command will sync your Drizzle schema with your Xata database.
pnpm db:push


Run the development server:
pnpm dev


Your application should now be running on http://localhost:3000.
</details>
<details>
<summary><strong>Environment Variables</strong></summary>
<br />
You'll need to create a .env file and populate it with the following keys.
Note: For deployment, remember to update the URLs to your production domain (e.g., https://screen-recording-and-sharing-app.onrender.com) in both your .env file and in your Google Cloud Console.
# Base URL for local development
NEXT_PUBLIC_BASE_URL=http://localhost:3000
BETTER_AUTH_URL=http://localhost:3000

# BetterAuth
BETTER_AUTH_SECRET=

# Google
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

# Xata
XATA_API_KEY=
DATABASE_URL_POSTGRES=
DATABASE_URL=

# Bunny
BUNNY_STORAGE_ACCESS_KEY=
BUNNY_LIBRARY_ID=
BUNNY_STREAM_ACCESS_KEY=

# Arcjet
ARCJET_API_KEY=


</details>
🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
📜 License
Distributed under the MIT License. See LICENSE for more information.
<div align="center">
<h3>Made with ❤️ by Your Name</h3>
<a href="https://github.com/your-username">GitHub</a>
·
<a href="https://twitter.com/your-username">Twitter</a>
·
<a href="https://linkedin.com/in/your-username">LinkedIn</a>
</div>
