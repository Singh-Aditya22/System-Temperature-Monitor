# System-Temperature-Monitor
Script to monitor system temperature for Acer laptops in ubuntu

### Steps to Run the `tempmon` Script as a Command  

1️ **Edit the script** (if needed):  
   ```bash
   nano /home/aditya-singh/tempmon.sh
   ```
   
2️ **Make it executable**:  
   ```bash
   chmod +x /home/aditya-singh/tempmon.sh
   ```

3️ **Move it to `/usr/local/bin/`** (to run as `tempmon` from anywhere):  
   ```bash
   sudo mv /home/aditya-singh/tempmon.sh /usr/local/bin/tempmon
   ```

4️ **Ensure execution permission**:  
   ```bash
   sudo chmod +x /usr/local/bin/tempmon
   ```

5️ **Run the script using**:  
   ```bash
   tempmon
   ```  

Now, you can execute `tempmon` like any regular command! 
