
# Installing Mods on Wake Servers BeamMP Server

Adding mods to your BeamMP server hosted on Wake Servers is a straightforward process. Follow these steps to ensure your mods are installed correctly and available for your players.

---

## **Step 1: Prepare Your Mod Files**

1. Download the mod you want to install from a trusted source (e.g., [BeamNG Repository](https://www.beamng.com/resources/)).
2. Ensure the mod is in `.zip` format and is compatible with the BeamMP server.

> **Tip**: Avoid renaming the mod files, as it may cause issues with loading them properly.

---

## **Step 2: Upload Your Mod to the Server**

1. Log in to your Wake Servers game panel.
2. Navigate to your BeamMP server instance.
3. Locate the **File Manager** section in the server dashboard.
4. Upload the `.zip` file to the following directory:
   ```
   /resources/mods/
   ```
   > **Note**: If the `mods` folder doesn’t exist, create it manually.

---

## **Step 3: Activate the Mod**

1. Open the server's configuration file (`server-config.json`) using the **File Editor** in the game panel.
2. Add the mod file name under the `mods` section:
   ```json
   "mods": [
       "modname.zip"
   ]
   ```
   Replace `modname.zip` with the exact name of the mod file.

3. Save the changes and restart your server.

---

## **Step 4: Test the Mod**

1. Join your BeamMP server using the BeamMP client.
2. Verify the mod is working by checking if:
   - New vehicles, maps, or features from the mod are available in-game.
   - No errors are displayed in the server console.

> **Troubleshooting**: If the mod doesn’t load, double-check the file name and ensure it’s uploaded to the correct directory.

---

## **Step 5: Share Mods with Players**

1. Provide your players with a link to download the mod (if not auto-downloaded by the server).
2. Encourage players to place the mod file in their local BeamNG directory:
   ```
   Documents/BeamNG.drive/mods/
   ```

---

## **FAQs**

### **What happens if a mod causes server crashes?**
- Simply remove the mod `.zip` file from the `/resources/mods/` directory and restart the server.

### **Can I install multiple mods at once?**
- Yes! Add each mod’s file name to the `mods` section of the `server-config.json` file.

### **Where can I find more mods?**
- Check out the [BeamNG Community Repository](https://www.beamng.com/resources/) for a wide selection of mods.

---

Congratulations! Your BeamMP server is now enhanced with custom mods. If you encounter any issues, don’t hesitate to reach out to Wake Servers support.
