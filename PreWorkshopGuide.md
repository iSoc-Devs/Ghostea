### Pre-Workshop Guide for Fullstack & Devops

Thank you for considering attending the tech workshop. We've detailed what you need to get ready.

Quick note: We'd highly advise installing everything locally to set you up for success in the future. However if this looks really, really challenging. You can access a lightweight vscode editor online here: https://github.dev/iSoc-Devs/Ghostea

---

#### 1. **Laptop & Internet Access**

- **Bring your laptop** with enough battery life, or bring your charger.
- Ensure you can connect to **Wi-Fi**, as we’ll be working online.

---

#### 2. **Set Up the Necessary Tools**

We’ll be using some free tools to work on the code. Here’s how to get started:

- **GitHub Account**  
  If you haven’t already, create an account on [GitHub](https://github.com/). This is where our code will live, and we’ll be interacting with GitHub to manage our project.

- **Install Visual Studio Code (VSCode)**  
  Download and install VSCode, a free and easy-to-use code editor, from [Visual Studio Code’s website](https://code.visualstudio.com/).

- **Install Git**  
  Git is a tool for managing code versions and tracking changes. Download and install it from [Git’s official website](https://git-scm.com/downloads). Follow the instructions on the website to install it on your computer.

---

#### 3. **Install VSCode Extensions for TypeScript**

We’ll be working on **Ghostea**, a TypeScript-based project, so these extensions will help with code quality and consistency:

- **ESLint**  
  This extension automatically checks for common JavaScript and TypeScript issues, helping ensure good code quality.

- **Prettier**  
  A code formatter that makes your code cleaner and easier to read. Prettier works well alongside ESLint to maintain consistent style.

To install an extension in VSCode:
1. Open VSCode.
2. Go to the Extensions view by clicking on the square icon on the sidebar.
3. Type the name of the extension (e.g., “ESLint”) and click **Install**.

---

#### 4. **Get Familiar with the Command Line and Basic Git Commands**

The **Command Line** (or **Terminal**) is a tool that allows you to interact with your computer using text commands instead of a graphical interface. Think of it as a way to give instructions directly to your computer. We’ll use the command line in this workshop to manage code with Git, a version control system.

To open the command line:
- On **Windows**: Open **Command Prompt** or **PowerShell** (or you can open the terminal directly in VSCode).
- On **macOS** and **Linux**: Open **Terminal** (or use the integrated terminal in VSCode).

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

---

#### 5. **Getting Started with the Ghostea Repository**

In the workshop, we’ll be working directly on the **Ghostea** fork of the **Ghost** open-source project. Follow the instructions in **Section 4** to:
- **Clone the Repository**: Download the [Ghostea repository](https://github.com/iSoc-Devs/Ghostea) to your laptop.
- **Create a Branch**: Work on your own branch to make changes safely.

---

#### 6. **Test Git Configuration (Optional but Helpful)**

To ensure Git recognizes you, you can configure it with your name and email (once Git is installed):
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

---

This guide will help you arrive ready to explore some hands-on coding and GitHub workflows. Looking forward to diving into the code with you!