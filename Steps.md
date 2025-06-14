

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

### ✅ **Step-by-Step: Create and Switch to `Rev1.1` Branch**

1. **Open Command Prompt**
   Navigate to your repo folder:

   ```bash
   cd C:\Users\YourName\Documents\GitTest
   ```

2. **Check current branch**

   ```bash
   git branch
   ```

   You should see `* main` as the current branch.

3. **Create and switch to a new branch `Rev1.1`**

   ```bash
   git checkout -b Rev1.1
   ```

   This creates the branch **and** switches to it.

4. **Make changes (optional)**
   Open `hello.py` and edit it, for example:

   ```python
   print("Hello, GitHub! This is Rev1.1.")
   ```

   Save the file.

5. **Add and commit changes**

   ```bash
   git add hello.py
   git commit -m "Updated hello.py for Rev1.1"
   ```

6. **Push the new branch to GitHub**

   ```bash
   git push -u origin Rev1.1
   ```

---

You’ll now see the new branch `Rev1.1` on GitHub under the branch dropdown.




You’ll be prompted to log in — follow the authentication steps (token-based if password no longer works).

---

Once done, refresh your GitHub repo page — you’ll see `hello.py` uploaded.
