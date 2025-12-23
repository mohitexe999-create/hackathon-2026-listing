# HOW TO FIX THE RED ERRORS

The "red" errors are happening because **Node.js** and **npm** are not being detected by the system. This means the required libraries (React, Next.js) are not installed.

### 1. Install Node.js
If you haven't already, download and install Node.js from [nodejs.org](https://nodejs.org).

### 2. RESTART VS CODE
**This is crucial.** After installing Node.js, you must completely close and reopen VS Code for it to recognize the `npm` command.

### 3. Run the Installation
Once VS Code is restarted, open the terminal (Ctrl+` or Terminal > New Terminal) and run:

```bash
npm install
```

### 4. Start the App
After the installation finishes, the red errors will vanish. You can then run:

```bash
npm run dev
```

**Note:** I created a file called `install.bat` in your folder. You can also try double-clicking that file in your file explorer to automatically install everything.
