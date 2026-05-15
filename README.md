# cursorrepo
GitHub repo for Cursor IDE

Here's how I did it.

First I install cursor IDE as instructed. I use the browser version instead of the linked version for safety.

Then I add the claude and codex (from chatgpt) as instructed. I clicked ctrl+shift+p followed by typing Claude and Codex for installation. Took me quite some time to figure out the extension symbol as I'm not familiar with cursor. I watched youtube videos on cursor basics as well as asking Qwen and Gemini by attaching screenshots to help me navigate the buttons and symbols on cursor.

After both claude and codex has been intalled. I logged in on both. Its quite harder to log in on codex due to issues with chatgpt login, but after I restarted my PC, the problem is solved.

Next is to create a GitHub account and create a repository which I named 'cursorrepo'(https://github.com/avicenamuzhaffara-rzr/cursorrepo)

Creating a GitHub repository automatically create a README.md file.

Next is to link the repository with Cursor. To do so, I must do a Git:Clone in the Command palette.

But because the Git has yet to beinstalled, it shows a Git Output error.

By adding @builtin Git and checking if the Git is installed then we move on to configure Git Path in Cursor in C:\Program Files\Git\bin\git.exe before restarting it.

After restarting cursor, I check the terminal using command git --version, showing the leatest Git version installed

After verifying the latest Git version oc terminal. The next thing is to add Git paths from my User files in computer. Adding bin and cmd path for Git (C:\Program Files\Git\bin and C:\Program Files\Git\cmd ).

After this has been done. A REDME.md file can be opened in Cursor IDE to be edited.

To push README.md file into github, run command to verify name and github email using
>git config user.name
>git config user.email

Press ctrl+s after writing down on Readme.md and the to commit use ctrl+shift + G before clicking the "+' icon and then clicking checkmark.

To Push, simply do Ctrl+Shift+P.