---

### ✅ **Step 1: Install Git and Python (if not already installed)**

* Download Git: [https://git-scm.com/download/win](https://git-scm.com/download/win)
* Download Python: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)
* During Python install, check “Add Python to PATH”.

---

### ✅ **Step 2: Create Your Python File**

1. Open **Notepad** or **VS Code**.
2. Type the following code:

   ```python
   print("Hello, GitHub!")
   ```
3. Save as `hello.py` in a folder, e.g., `C:\Users\YourName\Documents\GitTest`.

---

### ✅ **Step 3: Initialize Local Git Repository**

1. Open **Command Prompt**.
2. Navigate to your folder:

   ```bash
   cd C:\Users\YourName\Documents\GitTest
   ```
3. Initialize Git:

   ```bash
   git init
   ```

---

### ✅ **Step 4: Add Your Python File to Git**

```bash
git add hello.py
git commit -m "Initial commit - hello.py"
```

---

### ✅ **Step 5: Create a New Repository on GitHub**

1. Go to [https://github.com](https://github.com)
2. Click the **+** icon > **New repository**
3. Name: `hello-python`
4. Set to Public or Private
5. Do NOT initialize with README (uncheck it)
6. Click **Create repository**

---

### ✅ **Step 6: Push Code to GitHub**

1. Copy the repo URL (e.g., `https://github.com/YourUsername/hello-python.git`)
2. Back in Command Prompt:

```bash
git remote add origin https://github.com/YourUsername/hello-python.git
git branch -M main
git push -u origin main
```

You’ll be prompted to log in — follow the authentication steps (token-based if password no longer works).

---

Once done, refresh your GitHub repo page — you’ll see `hello.py` uploaded.
