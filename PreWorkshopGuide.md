### Pre-Workshop Guide

Thank you for considering attending the tech workshop. We've detailed what you need to get ready.

---

#### 1. **Laptop & Internet Access**

- **Bring your laptop** with enough battery life, or bring your charger.
- Ensure you can connect to **Wi-Fi**, as we’ll be working online.




**Everything else is totally optional!**

---

<details>
    <summary> Backend/ Devops </summary>

#### 2. **Set Up the Necessary Tools**

We’ll be using some free tools to work on the code. Here’s how to get started:

- **GitHub Account**  
  If you haven’t already, create an account on [GitHub](https://github.com/). This is where our code will live, and we’ll be interacting with GitHub to manage our project.

- **Install Visual Studio Code (VSCode)**  
  Download and install VSCode, a free and easy-to-use code editor, from [Visual Studio Code’s website](https://code.visualstudio.com/).

- **Install Git**  
  Git is a tool for managing code versions and tracking changes. Download and install it from [Git’s official website](https://git-scm.com/downloads). Follow the instructions on the website to install it on your computer.

- **Install Node.js**  
  Node.js is used to run javascript and typescript outside a browser. Install it from the [Node.js website](https://nodejs.org/en/download/package-manager).

**Quick note**: We'd highly advise installing everything locally to set you up for success in the future. However if it was really, really challenging you can access a lightweight vscode editor online here: https://github.dev/iSoc-Devs/Ghostea (doesn't have a terminal)

You could also use your [complimentary](https://docs.github.com/en/billing/managing-billing-for-your-products/managing-billing-for-github-codespaces/about-billing-for-github-codespaces#monthly-included-storage-and-core-hours-for-personal-accounts) monthly GitHub Codespaces allowance for a more fully featured completely online experience. Worthwhile; but it can take ten minutes to setup. If you're considering this option, it would great to set it up before the session. **This setup is especially useful if you're using a tablet with a keyboard.**

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/iSoc-Devs/Ghostea?quickstart=1)

---

#### 3. **Get Familiar with the Command Line and Basic Git Commands**

The **Command Line** (or **Terminal**) is a tool that allows you to interact with your computer using text commands instead of a graphical interface. Think of it as a way to give instructions directly to your computer. We’ll use the command line in this workshop to manage code with Git, a version control system.

To open the command line:
- On **Windows**: Open **Command Prompt** or **PowerShell** (or you can open the terminal directly in VSCode).
- On **macOS** and **Linux**: Open **Terminal** (or use the integrated terminal in VSCode).

---

Here are some key terms and commands. Don’t worry if they seem new; we’ll review them together!

- **Repository (Repo)**: This is a “project” or “folder” that contains all the code files we’ll be working on. It’s a central place where the project’s files, code history, and contributions are stored, usually on a platform like GitHub.

- **Fork**: A fork is a personal copy of someone else’s project that you can modify independently. When you fork a repository, you create your own version of it in your GitHub account. This allows you to experiment, make changes, and submit improvements to the original project. In this workshop, we’ll be working on the **Ghostea** fork of the open-source **Ghost** project.

- **Branch**: A branch is a parallel version of the repository that lets you work on changes without affecting the main codebase. Think of it as a “work-in-progress” space. By creating branches, you can isolate different tasks or features, test code, and keep your changes separate until they’re ready to be merged. For example, the main code may be on a branch called `main` or `master`, and you might create a new branch called `feature-update` to work on a new feature. This makes it easy to work on multiple things simultaneously without disrupting the main codebase.

**Basic Commands:**
- **Clone**: This copies the **Ghostea** repository from GitHub onto your laptop. Type the following in the command line:
  ```bash
  git clone https://github.com/iSoc-Devs/Ghostea.git
  ```
  This command will create a folder on your laptop with all the files from the Ghostea project.

- **Create a New Branch**: A branch is like a separate version of the project where you can make changes without affecting the main code. Creating a branch helps keep changes organized.

  After cloning, go into the Ghostea folder (type `cd Ghostea` in the command line), then create a branch with:
  ```bash
  git checkout -b your-branch-name
  ```
  Replace `your-branch-name` with something descriptive for the changes you plan to make.

- **Commit**: Think of this as “saving” your work with a note about what you changed.
  ```bash
  git commit -m "Your message here"
  ```

- **Push**: This uploads your changes to GitHub so others can see them.
  ```bash
  git push
  ```

For Mac and Linux, you can learn more in [this video](https://www.youtube.com/watch?v=I4EWvMFj37g).

---

#### 4. **Getting Started with the Ghostea Repository**

In the workshop, we’ll be working directly on the **Ghostea** fork of the **Ghost** open-source project. Follow the instructions in **Section 4** to:
- **Clone the Repository**: Download the [Ghostea repository](https://github.com/iSoc-Devs/Ghostea) to your laptop.
- **Create a Branch**: Work on your own branch to make changes safely.

---

#### 5. **Test Git Configuration (Optional but Helpful)**

To ensure Git recognizes you, you can configure it with your name and email (once Git is installed):
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

---


This guide will help you arrive ready to explore some hands-on coding and GitHub workflows. Looking forward to diving into the code with you!

Bonus. Watch these videos:
[![Watch the video](https://img.youtube.com/vi/zQnBQ4tB3ZA/maxresdefault.jpg)](https://youtu.be/zQnBQ4tB3ZA)
[![Watch the video](https://img.youtube.com/vi/ahCwqrYpIuM/maxresdefault.jpg)](https://youtu.be/ahCwqrYpIuM)
</details>

<details>
    <summary> Data Science - GenAI Focus </summary>


#### 2. Check out this workbook for more information

https://colab.research.google.com/drive/1wB7PYbLN9WV8OjsB7Azr1EjMNxxf5cLU?usp=sharing

</details>

<details>

<summary>
    Data Science - ML Training Focus
</summary>
https://colab.research.google.com/drive/1WwvqPy60jBuDp-mgVyUY7aWm8v9swcfG?usp=sharing 

Open this notebook in Google Colab, and save a copy somewhere so you can run it, make changes, etc.

</details>

<details>
    <summary>
        Frontend and UI/UX
    </summary>

Will include further details shortly.
</details>

<details>
    <summary>
        Using Tech in other disciplines
    </summary>

If you're working on your dissertation. Come with notes and thoughts about the challenges in capturing qualitative and quantitative data.

</details>

<details>
    <summary>
        Tech Sales/ Business Development
    </summary>

Lots of great context has been provided here: https://docs.google.com/document/d/129TNCBB6LZc14E4cwewxzSGxClhugJgmlPhz3nCrY6k
The workshop will focus more on the particular challenges in tech sales (as opposed to sales in other industries).
    
</details>
