
# 🗂️ Project Management App

A fully functional and responsive **Project Management Application** built with **React**, **Vite**, and **Tailwind CSS**. This app lets users create and manage projects with tasks seamlessly. It is deployed using **Azure Static Web Apps** with automated CI/CD via **GitHub Actions**.

---

## 🚀 Features

- 📁 Create and delete projects
- ✅ Add, view, and manage tasks for each project
- 🎨 Modern UI with Tailwind CSS
- ⚡ Fast development via Vite
- ☁️ Hosted on Azure Static Web Apps
- 🔄 Auto-deployment using GitHub Actions

---

## 🛠️ Tech Stack

| Tech            | Purpose                          |
|-----------------|----------------------------------|
| React           | Frontend UI library              |
| Vite            | Fast bundler & dev server        |
| Tailwind CSS    | Utility-first CSS framework      |
| Azure SWA       | Static hosting platform          |
| GitHub Actions  | CI/CD workflow for deployment    |

---

## 📁 Folder Structure

```
project-management-app/
├── dist/                  # Build output (after `npm run build`)
├── public/                # Static assets
│   ├── screenshots.png    # UI snapshots
├── src/                   # Application source
│   ├── assets/            # Static images
│   ├── components/        # Reusable UI components
│   ├── views/             # Main views/screens
│   ├── App.jsx            # Main app component
│   ├── main.jsx           # App entry point
├── .github/workflows/
│   └── azure-static-web-apps.yml # GitHub Actions config
├── index.html
├── index.css
├── vite.config.js
├── package.json
└── README.md
```

---

## 💻 Local Development

### Prerequisites
- Node.js v16+
- Git

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/project-management-app.git
   cd project-management-app
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start Development Server**
   ```bash
   npm run dev
   ```
   Open: [http://localhost:5173](http://localhost:5173)

---

## 🏗️ Build for Production

```bash
npm run build
```

Output will be placed in the `dist/` directory.

---

## 🌐 Azure Static Web Apps Deployment

### Step-by-Step Setup

1. **Install**: [VS Code Azure Tools Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-node-azure-pack)
2. **Login** to Azure inside VS Code
3. Open Command Palette and run:
   ```
   Azure Static Web Apps: Create Static Web App...
   ```
4. Fill out the prompts:
   - App location: `/`
   - API location: *(leave blank)*
   - Build output: `dist`

5. Azure generates a GitHub Actions workflow at:
   ```
   .github/workflows/azure-static-web-apps.yml
   ```

6. Push to GitHub → your app is automatically deployed to Azure.

---

## 🔴 Live Demo

> Replace this with your actual deployed URL:

**https://calm-water-00b367910.6.azurestaticapps.net**

---

## 📸 Screenshots

![Dashboard](./public/Screenshot-1.png)
![Task View](./public/Screenshot-2.png)

---

## 📌 To-Do / Roadmap

- [ ] Add authentication (Azure AD or Firebase)
- [ ] Add task priorities & due dates
- [ ] Integrate backend (e.g., Supabase or Firebase)

---

## 👏 Credits

This app is powered by:

- [React](https://reactjs.org)
- [Vite](https://vitejs.dev)
- [Tailwind CSS](https://tailwindcss.com)
- [Azure Static Web Apps](https://learn.microsoft.com/en-us/azure/static-web-apps/)
- [GitHub Actions](https://docs.github.com/en/actions)

