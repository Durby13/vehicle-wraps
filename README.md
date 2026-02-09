# SAESRPG - Custom Vehicle Wraps

Welcome to the official community vehicle wrap repository for **SAESRPG**.

This repository allows players and organisations to upload and manage custom vehicle wraps.

> **ℹ️ Need more info?**
> Detailed documentation and usage guides can be found on the [Wiki](https://github.com/saesrpg/vehicle-wraps/wiki).

## 🚀 Step 1: Getting Started

Before adding any files, you need to have your GitHub environment set up and your own copy of this repository.

### 1. New to GitHub?
If you are new to GitHub, please check out these official guides first:
* **Create an Account:** [Signing up for a new GitHub account](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)
* **Install the Tool:** [How to install and use GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop)

### 2. Fork the Repository
Once you are set up, you need to "Fork" this repo. This creates your own personal copy where you can make changes safely.
1.  **Click the "Fork" button** in the top-right corner of this page.
2.  Select your account as the destination.
3.  *Guide: [How to fork a repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo)*

### 3. Clone the Repository
Now that you have forked it, you need to download the files to your computer to add your images.
* Open GitHub Desktop (or your preferred tool).
* Select **File > Clone Repository**.
* Choose the repository you just forked (e.g., `your-username/vehicle-wraps`).
* *Guide: [How to clone a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)*

## 📂 Step 2: Choose Your Wrap Type

Identify which type of wrap you are adding and follow the specific instructions below.

| Wrap Type | For Who? | Requirement |
| :--- | :--- | :--- |
| **Donation Wraps** | Individual Players | Requires Donation Points. |
| **Organisation Wraps** | Groups, Gangs, Squads | For official organisations. |

## 👤 Option A: Donation Wraps (Players)

Wraps for individual users must follow a strict **username** and **sequential number** format.

### 1. Create the Folder Structure
Inside your forked repo (using GitHub Desktop or the web), navigate to: `RPGvehicleWrapAssets/wraps/custom/users/`

1.  Find or create a folder with your **exact username** (e.g., `ronseal`).
2.  Inside your user folder, create a new folder using the next **sequential number**.
    * *Example:* If `001` exists, name the new folder `002`.

**Example Path:**
`RPGvehicleWrapAssets/wraps/custom/users/ronseal/001/`

### 2. Add Required Files
Inside your numbered folder (e.g., `001`), add the following:

* **`wrap.png`** (Required)
    * The image file **must** be strictly named `wrap.png`.
    * Do not use other names (like `car.png` or `Wrap.png`).

* **`allowed.txt`** (Optional)
    * Create this file to restrict access.
    * List allowed SAES usernames, one per line.
    * *If omitted, the wrap is public.*

    **Example (`allowed.txt`):**
    ```text
    ronseal
    nanobob
    brophy
    ```

## 🏢 Option B: Organisation Wraps

Wraps for organisations are stored by organization type (gang, squad, group, etc.).

### 1. Navigate to the Folder
Inside your forked repo, navigate to: `RPGvehicleWrapAssets/wraps/custom/orgs/`

1.  Open the folder matching your organization type (e.g., `group`, `gang`, `squad`).
2.  **Do NOT create a sub-folder.** You simply drop the image file directly into this type folder.

**Example Path:**
`RPGvehicleWrapAssets/wraps/custom/orgs/group/`

### 2. Add Required Files
* **`<orgname>.png`** (Required)
    * The image file should be named after your organization (e.g., `soa.png`, `bope.png`).
    * *Note: Organisation wraps do not use `allowed.txt`.*

## 📤 Step 3: Submit Your Wrap

Once you have added your files to your forked repository:

1.  **Commit & Push:** Save your changes using GitHub Desktop (or your preferred tool) with a descriptive message.
    * *Example:* `Added wrap: ronseal/001` or `Added org wrap: soa.png`.
2.  **Open a Pull Request:**
    * Go to the "Pull Requests" tab in the original `SAESRPG/vehicle-wraps` repository.
    * Click **New Pull Request**.
    * Click the blue text that says **compare across forks**.
    * Select your fork in the **head repository** drop-down and submit.

## ✅ General Rules

* **File Format:** All images must be in **.PNG** format.
* **File Naming:**
    * **Users:** Must be `wrap.png`.
    * **Orgs:** Must be `orgname.png`.
* **Content:** Designs must comply with SAESRPG community guidelines.

## ❓ Troubleshooting

If you need help, contact support on Discord: [https://saesrpg.uk/discord](https://saesrpg.uk/discord)
