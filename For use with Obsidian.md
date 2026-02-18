

## On Mobile
TBD

## On Desktop

#### Windows 
##### 1. Install Obsidian and Git
1. Install Obsidian Notes from https://obsidian.md/download:
	- Download *Obsidian.exe*.
	- Open App Wizard and install as per usual.
2. Install Git from https://git-scm.com/install/windows:
	- Download *[Git for Windows/x64 Setup](https://github.com/git-for-windows/git/releases/download/v2.53.0.windows.1/Git-2.53.0-64-bit.exe)*.
	- Run App Wizard and go through the process.

##### 2. Create New Vault
1. Create a New Vault with any name, preferably "Multiverse"
2. Set the location to be in your Documents folder (recommended)

##### 3. Community Plugins
1. Go to *Settings > Community Plugins* and hit "Turn on community plugins".
2. Download the community plugin *Git* by *Vinzent*.

##### 4. Cloning
Open *Command Palette* on the sidebar or press *Ctrl+P* and run the command 
	```Git: Clone an existing remote repo```
	 with the following inputs:
1. Enter Remote URL : https://github.com/astralis17/Multiverse.git
2. Enter Directory...    : Input *Multiverse* or whatever the name of the vault is
3. Specify Depth...      : Leave blank 
	A folder with the name of the vault should have appeared in the vault.

##### 5. Folder Setup
Close Obsidian and open file explorer.
1. Navigate to the vault folder (It should only have a folder with the same name as it self)
2. Select the folder with the same name and move it to the parent folder (The folder that contains the vault)
E.G. The Vault is called *Multiverse* and is stored inside the *Documents* folder. Within *Multiverse* there should be another folder of the same name. Move that folder to *Documents*.
This will display a popup asking about merging files, accept and allow it to replace all files.

##### 6. Credentials 
1. Go to *Settings > Git > Commit Author* and enter your GitHub account name and associated email address.
2. Create a blank commit and push, this will prompt Git Credential Manager to open, choose Sign in with GitHub or enter username and password (or ghp key) manually.