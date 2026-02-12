# How to Upload This Project to GitHub

Follow these steps to push your local Glassdoor EDA project to a new GitHub repository.

## Prerequisites
*   You must have `git` installed on your machine.
*   You must have a GitHub account.

## Step 1: Create a New Repository on GitHub
1.  Log in to your GitHub account.
2.  Click the **+** icon in the top-right corner and select **New repository**.
3.  **Repository name:** `GlassdoorJobposting` (or any name you prefer).
4.  **Description:** "Exploratory Data Analysis of 12,000+ Glassdoor Job Postings using Python and Seaborn."
5.  **Visibility:** Public.
6.  **Initialize:** Do **NOT** add a README, .gitignore, or License (we already created these locally).
7.  Click **Create repository**.

## Step 2: Initialize Git Locally
Open your terminal (PowerShell or Command Prompt) and navigate to your project folder:

```bash
cd "c:\Users\palra\Desktop\Agentic ai\GlassdoorJobposting"
```

Run the following commands:

1.  **Initialize Git** (if not already done):
    ```bash
    git init
    ```

2.  **Add all files to staging:**
    ```bash
    git add .
    ```

3.  **Commit the files:**
    ```bash
    git commit -m "Initial commit: Glassdoor EDA project with analysis and documentation"
    ```

4.  **Rename branch to main:**
    ```bash
    git branch -M main
    ```

## Step 3: Connect to GitHub and Push

1.  **Add the remote origin** (Replace `YOUR_USERNAME` with your actual GitHub username):
    ```bash
    git remote add origin https://github.com/YOUR_USERNAME/GlassdoorJobposting.git
    ```

2.  **Push the code:**
    ```bash
    git push -u origin main
    ```

## Step 4: Verify
Refresh your GitHub repository page. You should see your code, the comprehensive README, and the green badges!

---

**Note:** The dataset `finaldata2.csv` is approximately 5.7MB, which is well within GitHub's limits. You can safely push it.
