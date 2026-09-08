# 🚀 How to Setup Your GitHub Profile & Snake Game Streak

Follow these simple steps to apply your new profile README and activate the **Snake Game on your Contribution Streak**:

---

### Step 1: Create your Special Profile Repository on GitHub
1. Go to [GitHub](https://github.com/new).
2. Create a new public repository named **exactly** `chhaviTiwari63` (matching your username).
3. Check the box to **"Initialize this repository with a README"**.

---

### Step 2: Copy the Profile README
1. Copy the contents of [`README.md`](./README.md).
2. Paste it into the `README.md` of your `chhaviTiwari63` repository and commit the changes.

---

### Step 3: Add the Snake Game GitHub Action
1. In your `chhaviTiwari63` repository, create a new file path:
   `.github/workflows/snake.yml`
2. Copy and paste the contents of [`snake.yml`](./.github/workflows/snake.yml) into this file.
3. Commit the file.

---

### Step 4: Enable Workflow Write Permissions (Crucial for Snake Game)
1. In your `chhaviTiwari63` repository, go to **Settings** > **Actions** > **General**.
2. Scroll down to **Workflow permissions**.
3. Select **"Read and write permissions"**.
4. Click **Save**.

---

### Step 5: Trigger the Snake Game Action
1. Go to the **Actions** tab in your repository.
2. Click on **"Generate Contribution Snake Game"** on the left menu.
3. Click **"Run workflow"** > **"Run workflow"**.
4. Once it finishes running (takes ~30 seconds), it will automatically create an `output` branch with your animated snake SVG!
5. Now, refresh your GitHub profile page to see the animated Snake eating your contribution streak, along with your live streak stats cards! 🎉
