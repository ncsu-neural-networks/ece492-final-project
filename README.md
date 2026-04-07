# Github Repository Instructions
1. Download id_rsa_openssh from the ece492-final-project Github repository
2. Upload ssh.sh and id_rsa_openssh to JupyterHub directory
3. Open the Terminal from Other in the JupyterHub Launcher
4. Modify the ssh.sh script permissions so that it is an executable: $ chmod 700 ~/ssh.sh
5. Execute the ssh.sh script which will configure ssh to work with the Github Repository: $ ./ssh.sh
6. Use the JupyterHub File Browser in the side panel to open the directory ece492-final-project
7. Navigate to the Github integration using the JupyterHub side panel
8. Initalize the local directory
9. The terminal must be used to run Git commands

# Github commands
1. $ Git checkout -b working
2. $ Git add .
3. $ Git commit -m "commit message"
4. $ Git push
5. $ Git pull
