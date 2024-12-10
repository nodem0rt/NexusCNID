# Nexus running via CLI

### Step 1: Register and Get Prover ID
1. Go to the web: [beta.nexus.xyz](https://beta.nexus.xyz).
2. Register using your email in the profile section (if the email not coming you can try again later).
3. Get the prover ID by inspecting the website :
   - Open your Chrome browser's Developer Tools
   - Go to the "Console" tab and run the following command:
     ```javascript
     localStorage.getItem('flutter.proverId');
     ```
4. Copy the `flutter.proverId` value.

---

### Step 2: Run Nexus CLI mode

1. **Clone Repository**
   ```bash
    git clone https://github.com/nodem0rt/NexusCNID.git
    cd nexusws

2. Create the screen (Sudo apt install screen if your server didn't setup before)
   ```
   screen -S nexus
   ```
3. Change the file permissions
   ```
   chmod +x NexusCNID.sh
   ```
4. Run the script
   ```
   ./NexusCNID.sh
   ```
5. Voila ! now you can detach the screen
   ctrl-A+D
---
<br>
