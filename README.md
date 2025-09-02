# NVM_setup_for_windows
NVM (Node version Manager) is a tool to manage multiple version of node

### Node.Js download for winsows 
1. At first download the Node.js. 
2. Install it.
3. Add the path into system variable.

```
Windows Installer (.msi)
https://nodejs.org/en/download/ 

```
### Open cmd and check the version
```
node -v
npm -v

```
### NVM Set up 
1. Go to the below link.
```
https://github.com/coreybutler/nvm-windows/releases/tag/1.1.12
```
2. Go to the assets section.
3. select the nvm-setup.zip or nvm-setup.exe

```
https://github.com/coreybutler/nvm-windows/releases/download/1.1.12/nvm-setup.zip
```
3. extract the folder and run nvm-setup file
4. Install it.
5. Add the path into system varible.

### check the nvm version
```
nvm -v
```
6. it shows 1.1.12 version for nvm.

### Then install required version which is available for your project.
1. if latest version is needed , then run the command
```
nvm install latest
nvm use (latest version)
```
2. any older version is required, then put it that version instead of latest version e.g (nvm install 14).

### If you check all nvm list
```
nvm list available
```

### If any error occur otherwise skip it
1. At first check the admin permission
2. Check the nvm location 
```
nvm root
```
3. Go to the location.
4. Click the right button of that folder.
5. Open the security tab.
5. Edit the permission button (full control, read, write)

### Again install the nvm as before

### If it does not work
1. Go to the control panel>program>uninstall nvm
2. perform all operation again
