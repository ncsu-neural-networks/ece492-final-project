# ece492-final-project

# Github Repository Instructions
1. Install Pageant https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
2. Download id_rsa_private.ppk, ssh.sh, and id_rsa_openssh from the ece492-final-project Github repository
3. Add id_rsa_private.ppk to Pageant which should be running in the taskbar
4. Upload ssh.sh and id_rsa_openssh to JupyterHub directory
5. Open the Terminal from Other in the JupyterHub Launcher
6. Modify the ssh.sh script permissions so that it is an executable: $ chmod 400 ~/ssh.sh
7. Execute the ssh.sh script which will configure ssh to work with the Github Repository: $ ./ssh.sh
8. Use the JupyterHub File Browser in the side panel to open the directory ece492-final-project
9. Navigate to the Github integration using the JupyterHub side panel
10. Initalize the local directory
10. The terminal must be used to run Git commands

# Github commands
1. $ Git add .
2. $ Git commit -m "commit message"
3. $ Git push
4. $ Git checkout -b branch-name
