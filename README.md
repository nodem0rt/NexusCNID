# NEXUS XYZ

Run Nexus via CLI mode: 
Step 1: Register and Get Prover ID
Go to the web: https://beta.nexus.xyz.
Register using your email in the profile section. (if email not coming just wait for further info)
Inspect the website to get the prover ID:
Open the browser's Developer Tools (F12 or right-click and select "Inspect").
Go to the "Console" tab and run the following command:
localStorage.getItem('flutter.proverId');
Copy the flutter.proverId value.
Step 2: Run Nexus
Clone the repository
 git clone https://github.com/nodem0rt/NexusCNID.git
 cd NexusCNID
Process on screen
screen -S nexus
Change File Permissions
chmod +x nexus.sh
Run the script
./nexus.sh
voila! now you can detach screen (ctrl + AD)
