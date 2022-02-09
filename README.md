# Keylogger

## Remote persistent keylogger for Windows and Linux.

Features:
- Logs keys pressed on keyboard
- Sends reports by email.
- Starts with system startup.
- Works with Linux and Windows.
- Does not require root or admin privlages.


## Installation

### 1. Nvigate to the /opt directory (optional):
```
$ cd /opt/
```

### 2. Clone the repo
```
$ git clone https://github.com/dharun-narayanan/Keylogger.git
```

### 3. Navigate into zLogger’s directory
```
$ cd Keylogger
```

### 4. Run the installer
```
$ bash install.sh
```
PS: this might take some time as it’ll install all the programs and libraries needed by Keylogger.

### 5. Done, now you can run zLogger from this working directory using the following command
```
$ python zlogger.py
```

## Removing the keylogger:

- Go to star, type regedit and run the first program, this will open the registry editor.
- Navigate to the following path Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run
- There should be an entry called winexplorer, right click this entry and select Delete.
- Go to your user path > AppData > Roaming, you’ll see a file named “Windows Explorer.exe”, this is the keylogger, right click > Delete.
