# 🧠 Quiz App

A dynamic and responsive **Quiz Application** built using **React**, **Vite**, and **Tailwind CSS**. Users can take multiple quizzes with various questions and receive instant feedback.
Deployed on **Azure Static Web Apps** with **CI/CD via GitHub Actions**.

---

## 🚀 Features

* ✅ Take interactive quizzes
* 🧩 Multiple question types
* 💯 Instant score feedback
* 🎨 Stylish and responsive UI with Tailwind CSS
* ⚡ Fast build and dev experience via Vite
* ☁️ Deployed on Azure Static Web Apps
* 🔄 Auto-deployment using GitHub Actions

---

## 🧰 Tech Stack

| Tech           | Purpose                        |
| -------------- | ------------------------------ |
| React          | Frontend UI framework          |
| Vite           | Fast bundler & dev server      |
| Tailwind CSS   | Utility-first CSS styling      |
| Azure SWA      | Static site hosting            |
| GitHub Actions | CI/CD for automatic deployment |

---

## 📁 Folder Structure

```bash
quiz-app/
├── dist/                       # Build output (after `npm run build`)
├── public/                     # Static assets
│   ├── favicon.ico             
│   └── ...                     
├── src/                        # Source code
│   ├── components/             # React components
│   ├── pages/                  # Main page layouts
│   ├── App.jsx                 # Main app component
│   ├── main.jsx                # Entry point
│   └── index.css               # Tailwind and base styles
├── .github/workflows/
│   └── azure-static-web-apps.yml  # GitHub Actions deployment file
├── index.html
├── vite.config.js
├── package.json
└── README.md
```

---

## 🧪 Local Development

### Prerequisites:

* Node.js v16+
* Git

### Steps:

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/quiz-app.git
cd quiz-app
```

2. **Install Dependencies**

```bash
npm install
```

3. **Start Development Server**

```bash
npm run dev
```

Visit: [http://localhost:5173](http://localhost:5173)

---

## 🏗️ Build for Production

```bash
npm run build
```

This will generate optimized files in the `dist/` folder.

---

## 🚀 Azure Static Web Apps Deployment

### Step-by-Step Azure Setup

1. **Install** VS Code Azure Tools Extension Pack
2. **Login** to Azure inside VS Code
3. Open the Command Palette and run:

```bash
Azure Static Web Apps: Create Static Web App...
```

4. Fill in:

   * App location: `/`
   * API location: *(leave blank)*
   * Output location: `dist`
5. Azure creates a GitHub Actions workflow:
   `.github/workflows/azure-static-web-apps.yml`
6. Every push to the repo triggers auto build & deployment

---

## 🔗 Live Demo

Add your Azure Static Web Apps live link here:
Example: [https://quiz-master-12345.z13.web.core.windows.net]([https://quiz-master-12345.z13.web.core.windows.net](https://calm-water-00b367910.6.azurestaticapps.net))

---

## 📸 Screenshots

![Question View](https://github.com/AniketP117/QuizApp/blob/master/public/Screenshot%202025-05-27%20212601.png)
![Results Page](https://github.com/AniketP117/QuizApp/blob/master/public/Screenshot%202025-05-27%20212704.png)
![Results Page](https://github.com/AniketP117/QuizApp/blob/master/public/Screenshot%202025-05-27%20212728.png)

---

## 🙌 Credits

Thanks to the following tools:

* [React](https://reactjs.org)
* [Vite](https://vitejs.dev)
* [Tailwind CSS](https://tailwindcss.com)
* [Azure Static Web Apps](https://azure.microsoft.com/en-us/services/app-service/static/)
* [GitHub Actions](https://github.com/features/actions)

---

## 🛣️ To-Do / Roadmap

* [ ] Add category selection for quizzes
* [ ] User login via Azure AD or Firebase
* [ ] Leaderboard & score history
* [ ] Backend integration (e.g., Supabase or Firebase)
