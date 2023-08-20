# DebHealthUtil
The Microsoft Windows System File Checker tool but for Debian to achieve the ultimate unbreakable Linux install

## How?

### Getting a healthy image:
A Github workflow creates a clean install of Debian, creates a Timeshift snapshot of it, and uploads the image to releases

### Keeping your OS preferences:
- A declarative approach is used to make replicable Debian systems by a configuration file that this program recognizes and processes.

It contains all the packages you want installed, and what commands to execute directly after the snapshot restoration process.
- A directory will be generated that contains your machines hardware dependent and user configuration files.

Additionally a second directory can be made that you can place whatever /etc/ files you want to be kept during the snapshot restoration process.

- Your home direct

### What changes:
- All required missing system files restored
- Any binary, temporary or configuration files that are not included by defualt are wiped out from the root filesystem
- The system will most likley feel cleaner, and less bloated & buggy.
