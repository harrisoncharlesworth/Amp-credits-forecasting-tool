# Deployment Instructions

## Option 1: Using GitHub CLI (Recommended)

1. **Install GitHub CLI** (if not already installed):
   ```bash
   # On macOS
   brew install gh
   
   # On Windows
   winget install --id GitHub.cli
   ```

2. **Authenticate with GitHub**:
   ```bash
   gh auth login
   ```
   Follow the prompts to authenticate with your GitHub account.

3. **Create the repository**:
   ```bash
   gh repo create amp-usage-model --public --description "Predictive forecasting tool to model and budget Amp spend as AI adoption scales across teams"
   ```

4. **Push the code**:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/amp-usage-model.git
   git branch -M main
   git push -u origin main
   ```

## Option 2: Using GitHub Web Interface

1. **Go to GitHub.com** and sign in
2. **Click the "+" icon** in the top right corner
3. **Select "New repository"**
4. **Repository details**:
   - Repository name: `amp-usage-model`
   - Description: `Predictive forecasting tool to model and budget Amp spend as AI adoption scales across teams`
   - Visibility: Public
   - Don't initialize with README (we already have one)

5. **After creating, run these commands**:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/amp-usage-model.git
   git branch -M main
   git push -u origin main
   ```

## Option 3: Quick Deploy (Current Directory Ready)

Your local repository is already set up! Just need to:

1. Create the repo on GitHub (using either method above)
2. Add the remote origin
3. Push the code

## GitHub Pages Deployment (Optional)

To make it accessible via a web URL:

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

Your site will be available at: `https://YOUR_USERNAME.github.io/amp-usage-model/`

## Files Ready for Deployment

✅ `amp_growth_model (1).html` - Main application
✅ `index.html` - Main application  
✅ `README.md` - Project documentation
✅ `.gitignore` - Git ignore rules
✅ Git repository initialized and committed

## Next Steps

1. Choose your preferred deployment method above
2. Replace `YOUR_USERNAME` with your actual GitHub username
3. Run the commands in your terminal
4. Your Amp Usage Growth Model will be live on GitHub!
