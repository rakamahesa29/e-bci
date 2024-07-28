# WordPress Setup and Configuration Guide

## How to Set Up a Fresh WordPress Installation

1. **Create Database in Localhost**
   - Open phpMyAdmin or your preferred database management tool.
   - Create a new database with your desired name.

2. **Upload WordPress Files**
   - Download WordPress from [wordpress.org](https://wordpress.org/download/).
   - Extract the files and upload them to your local server directory (e.g., `htdocs` or `www`).
   - Extract Zip `Plugin` in folder plugin.

3. **Connect to the Database**
   - Open your browser and navigate to the URL where you uploaded WordPress.
   - Follow the installation wizard and enter the details of the newly created database.

4. **Create Username and Password**
   - During the installation process, create a username and password for your admin account.
   - Complete the installation process.

5. **Login to the WordPress Dashboard**
   - Navigate to `http://localhost/wp-admin` and log in using the credentials you just created.

## How to Export WordPress Themes, Plugins, and Database

1. **Open WordPress Dashboard**
   - Log in to your WordPress dashboard.

2. **Go to the Plugin Menu**
   - Click on the `Plugins` menu in the sidebar.

3. **Search for the Plugin "All-in-One WP Migration"**
   - Use the search box to find the "All-in-One WP Migration" plugin.

4. **Install the Plugin**
   - Click `Install Now` and then `Activate`.

5. **Export Data**
   - Go to the `All-in-One WP Migration` menu in the sidebar.
   - Select the `Export` submenu.
   - Choose the desired export format and follow the instructions to complete the export.

6. **Import Data**
   - Go to the `All-in-One WP Migration` menu in the sidebar.
   - Select the `Import` submenu.
   - Upload the backup file that you downloaded from Google Drive or another source.

## How to Increase Maximum Upload File Size in WordPress

1. **Go to the `.htaccess` File**
   - Locate the `.htaccess` file in the root directory of your WordPress installation.
   - Open this file with a text editor.

2. **Add This Code After the `</IfModule>` Tag and Save**
   ```apache
   php_value upload_max_filesize 128M
   php_value post_max_size 128M
   php_value memory_limit 256M
   php_value max_execution_time 300
   php_value max_input_time 300

## Username Password After Theme Imported
- Username: admin_bci
- Password: @BciCommerce2024
- Backup Link: https://drive.google.com/file/d/1UVL5AnLudusI3cyo6T7nxm-WauJlZYK0/view?usp=sharing
