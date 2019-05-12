# Quick Start: Install, Configure, and Connect ownCloud Server

## Introduction

ownCloud is an open source file-sharing server that lets you access your private data from your desktop or mobile device. [ownCloud](https://owncloud.org/) is created and supported by a community of users and developers from around the world. It is available in both community and enterprise editions.

In this Quick Start:

* If you are an ownCloud administrator, you will [Install and Configure an ownCloud Server](#admin).
* If you are an ownCloud user, you will [Connect to ownCloud Using Desktop Client](#user).

## Install and Configure an ownCloud Server <a name="admin"></a>

### Overview

This section is intended for administrators who want a non-technical option to install and configure an ownCloud server using the Installation Wizard. Once completed, you will be ready to enable client connections and add users.

Not an administrator?

If you are a user and want to connect to an ownCloud server, refer to the section [Connect to ownCloud Using Desktop Client](#user).

### Before You Begin

Before installing ownCloud:

* Familiarize yourself with [installation options](https://doc.owncloud.org/server/10.1/admin_manual/installation/index.html) to know which best suits your needs.

> <b>Note:</b>This guide covers installation using the wizard only.

* Review the ownCloud [prerequisites](https://doc.owncloud.org/server/10.1/admin_manual/installation/manual_installation.html#prerequisites).
* Review the [system requirements](https://doc.owncloud.org/server/10.1/admin_manual/installation/system_requirements.html).
* Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).

### Download and Launch ownCloud Appliance

Appliance enables non-technical users to deploy ownCloud quickly and easily using VirtualBox. It is set up and configured with a secure connection and the ownCloud Proxy app. Appliance supports up to 500 users.

To launch Appliance:

1. Go to the [ownCloud Download Page](https://owncloud.org/download/).
2. From the Appliance section, download the VirtualBox OVA image file.
3. Run VirtualBox.
4. Select <b>File > Import Appliance</b> to run the Import wizard.
5. Load the OVA image file and agree to the terms and conditions.
6. Configure your domain and network settings.

### Run Appliance

To deploy your ownCloud server, you will need to activate Appliance when you run it for the first time by providing a valid email address. Follow the Appliance activation wizard prompts on-screen.

To run Appliance:

1. Open your web browser.
2. Enter [https://192.168.1.35](https://192.168.1.35/) in the address bar.
3. Enter a valid email address to activate.
4. Download the license sent to your email.
5. Click <b>Upload License File</b> on the activation screen and select the file <b>ucs.license</b>.
6. Click <b>Finish</b>.

### Run the Installation Wizard

You should now see the Univention Portal. From here, you can run the ownCloud Installation wizard to create your server.

To run the Installation Wizard:

1. From the Univention Portal, under Applications, click <b>ownCloud</b> to open the login screen.
2. Enter "Administrator" for username and the password you used when setting up the Appliance.
3. Click <b>Enter</b>.

The dialog box "A safe home for all your data" is displayed. Your ownCloud server is now ready to use.

### Configure Your Server

You can manage your ownCloud server settings from your browser, including such as adding a profile picture and changing your notification settings.

To configure your ownCloud server, select <b>Administrator > Settings</b> in the upper-right corner.

### Add a New User Account

Manage local system settings, such as favorites, users, devices, and software, in the Univention Portal.

To add a new user account as an administrator:

1. Click the UCS "System and domain settings" icon in the Univention Portal.
2. Select <b>Users</b> and click <b>Users</b> again.
3. Click <b>Add</b> from the top row.
4. Enter the user account details in the wizard and click <b>Create User</b>.

## Connect to ownCloud Using Desktop Client <a name="user"></a>

### Overview

This section is intended for users who want to access their private data by connecting to an ownCloud server using the ownCloud Desktop Client. You can also access your data using Android, iPhone, or other devices.
For instructions on how to access ownCloud from a mobile device, refer to the [ownCloud documentation page](https://doc.owncloud.org/server/).

### Before You Begin

Before installing ownCloud for Desktop Client:

* Set up your ownCloud account.
* Contact your administrator if you do not have an account.
* Review the [system requirements](https://doc.owncloud.org/server/10.1/admin_manual/installation/system_requirements.html).

### Download and Install ownCloud Desktop Client

The ownCloud Desktop Client keeps your data synced. Select one or more directories on your local machine for access to all your files from any location.

To install the ownCloud Desktop Client:

1. From your browser, go [to https://owncloud.org/download/#owncloud-desktop-client-windows](https://owncloud.org/download/#owncloud-desktop-client-windows).
2. Choose your system format and click <b>Download</b>. Your download file is saved to your local machine.
3. Open the file you just downloaded to begin installation.
4. Enable "Launch ownCloud after finish" and click <b>Finish</b>.

To connect to ownCloud Server:

1. Enter the server address you want to connect to and click <b>Next</b>.

> <b>Note:</b> If you do not know the server address, check with your administrator.

1. Select "Trust this certification anyway" and click <b>OK</b>.
2. Enter your username and password and click <b>Next</b>.
3. Configure your local folder options and click <b>Connect</b>.

You are now ready to begin syncing files with the ownCloud server.
