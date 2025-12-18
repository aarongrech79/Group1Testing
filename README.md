# Group1Testing

## ⚠️ IMPORTANT: Read This First

**Before writing any HTML code, please read the [HTML Style Guide](HTML_STYLE_GUIDE.md).**

This guide contains:
- Required page templates
- Common component patterns
- Accessibility requirements (WCAG AA compliance)
- Class naming conventions
- Form and button standards
- Testing checklist

Following the style guide ensures our code is **consistent, accessible, and maintainable** across the team.

---

## Quick Links

- 📋 [HTML Style Guide](HTML_STYLE_GUIDE.md) - **READ THIS BEFORE CODING**

---

## Setting Up with Visual Studio Code

### 1. Clone the Repository

**Option A: Using VS Code**
1. Open Visual Studio Code
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
3. Type "Git: Clone" and select it
4. Enter the repository URL: `https://github.com/aarongrech79/Group1Testing.git`
5. Choose a folder location on your computer
6. Click "Open" when prompted

**Option B: Using Terminal**
```bash
git clone https://github.com/aarongrech79/Group1Testing.git
cd Group1Testing
code .
```

### 2. Install Recommended Extensions (Optional but Recommended)

For better HTML/CSS development:
- **Live Server** - Launch a local development server with live reload
- **HTML CSS Support** - CSS Intellisense for HTML
- **Prettier** - Code formatter

### 3. Start Working

1. Read the [HTML Style Guide](HTML_STYLE_GUIDE.md)
2. Use the provided templates and components
3. Test your code against the accessibility checklist
4. Commit and push your changes
5. Submit your PR for review

---

## How to Fork and Create a Pull Request

### Step 1: Fork the Repository

1. Go to the repository on GitHub: `https://github.com/aarongrech79/Group1Testing`
2. Click the **"Fork"** button in the top-right corner
3. This creates a copy of the repository under your GitHub account

### Step 2: Clone Your Fork in VS Code

1. Open Visual Studio Code
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
3. Type "Git: Clone" and select it
4. Enter **your fork's URL**: `https://github.com/YOUR-USERNAME/Group1Testing.git`
5. Choose a folder location and open the repository

### Step 3: Create a New Branch

1. In VS Code, click on the branch name in the bottom-left corner (it says "main")
2. Click **"Create new branch..."**
3. Name your branch descriptively (e.g., `feature/add-checkout-page` or `fix/button-styles`)
4. Press Enter

**Or use the terminal:**
```bash
git checkout -b feature/your-feature-name
```

### Step 4: Make Your Changes

1. Read the [HTML Style Guide](HTML_STYLE_GUIDE.md)
2. Write your code following the guidelines
3. Test your changes
4. Save all files

### Step 5: Commit Your Changes

**Using VS Code's Source Control:**
1. Click the Source Control icon in the left sidebar (or press `Ctrl+Shift+G`)
2. Review your changes
3. Stage files by clicking the **"+"** icon next to each file
4. Enter a descriptive commit message (e.g., "Add checkout page with accessible forms")
5. Click the **"✓ Commit"** button

**Or use the terminal:**
```bash
git add .
git commit -m "Your descriptive commit message"
```

### Step 6: Push Your Branch

1. In the Source Control panel, click **"Publish Branch"** (for new branches) or the sync icon
2. This pushes your changes to your fork on GitHub

**Or use the terminal:**
```bash
git push origin feature/your-feature-name
```

### Step 7: Create a Pull Request

1. Go to your fork on GitHub: `https://github.com/YOUR-USERNAME/Group1Testing`
2. You'll see a banner saying **"Compare & pull request"** - click it
3. Make sure:
   - Base repository: `aarongrech79/Group1Testing`
   - Base branch: `main`
   - Your fork and branch are selected
4. Write a clear title and description of your changes
5. Click **"Create pull request"**

### Step 8: Wait for Review

- Team members will review your PR
- Make any requested changes by committing to the same branch
- Once approved, your changes will be merged into the main repository

---

## Keeping Your Fork Up to Date

If the main repository has been updated, sync your fork:

**Using VS Code:**
1. Press `Ctrl+Shift+P` and type "Git: Pull"
2. Select the option to pull from upstream

**Using Terminal:**
```bash
# Add the original repo as upstream (one-time setup)
git remote add upstream https://github.com/aarongrech79/Group1Testing.git

# Fetch and merge updates
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
```
