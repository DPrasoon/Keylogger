# Keylogger
A simple Python language based keylogger.

## Downloading & Installation

1. Download and extract the keylogger.pyw file.

```bash
git clone https://github.com/DPrasoon/keylogger.git
```

2. Download and install [Python](https://www.python.org/downloads/) (v3.4 or higher recommended)

3. Install **pynput** library using command line.

```console
pip install pynput
```

## Usage
### Windows
1. Double click the keylogger.pyw file.

### Linux
1. Give permissions to the file.
```bash
sudo chmod +rwx keylogger.pyw
```
2. Run the file.
```bash
./keylogger.pyw
```

## Output
As soon as a key is pressed, it will be logged into the ***log.txt*** file, present in the directory where the keylogger.pyw file is existing.


## Working

This script logs the keystrokes made by the user using **pynput** library, which can be accessed later to keep track of the users.

## Used Packages and Modules

### pynput.Keyboard
This package contains classes for controlling and monitoring the keyboard.

* **Key** - to define different keys

* **Listener** - to monitor the keyboard

* **on_press()** - to perform some defined action when a key is pressed

* **on_release()** - to perform some defined action when a key is released

* **write_file()** - to write  output in a file


## Developed by
Git - [DPrasoon](https://github.com/DPrasoon) (Suggestions and improvements are appreciated)
