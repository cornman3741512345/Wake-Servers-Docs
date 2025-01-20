
# Installing Mods On BeamMP Server

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

!!! warning "Warning"
    You can not upload more than ***`100mb`*** to the webpanel. In order to upload a high size file you must use ***`SFTP`*** under the ***`Settings Tab`*** of your server.

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
