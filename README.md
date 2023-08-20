# DebHealthUtil
The Microsoft Windows System File Checker tool but for Debian to achieve the ultimate unbreakable Linux install.

## How?

### Getting a healthy image
A Github workflow creates a clean install of Debian, creates a Timeshift snapshot of it, and uploads the image to releases

### Restoring your OS preferences
- A declarative approach is used to make replicable Debian systems by a configuration file that this program recognizes and processes.
It contains all the packages you want installed, and what commands to execute directly after the restoration process
