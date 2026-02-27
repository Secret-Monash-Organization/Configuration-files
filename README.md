## Using the Repository LTspice Configuration

This repository includes a preconfigured `LTspiceXVII.ini` file. You can replace your local LTspice configuration with this file to apply the same schematic and editor settings outlined inside week 1 workshop slides :) .
**Please note this will replace your existing LTSpice settings so make sure you create a backup**


---

## Windows Instructions

LTspice stores its user configuration at:

```
C:\Users\<YourUsername>\AppData\Roaming\LTspiceXVII.ini
```

### Step 1 - Close LTspice

Ensure LTspice is not running before modifying the configuration file.

### Step 2 - Backup Existing Configuration

Navigate to:

```
C:\Users\<YourUsername>\AppData\Roaming\
```

Rename the existing file:

```
LTspiceXVII.ini -> LTspiceXVII_backup.ini
```

### Step 3 - Copy the Repository Configuration

Copy the provided `LTspiceXVII.ini` from this repository into:

```
C:\Users\<YourUsername>\AppData\Roaming\
```


### Step 4 - Launch LTspice

Start LTspice normally. The application will now use the configuration supplied in this repository.

---


Restart LTspice to restore your previous configuration.
