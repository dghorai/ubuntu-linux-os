# ubuntu-linux-os
Learning and sharing practical experience of Ubuntu Desktop

### Downloading and Installation of Ubuntu Desktop
1. Download Ubuntu desktop: [Link](https://ubuntu.com/#download)
2. Install Ubuntu Desktop: [Link](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)

### Create Python Virtual Environment and Install Necessary Packages
- Open Terminal
- sudo apt install python3-virtualenv
- python3 --version
- virtualenv -p python3.10 venv (creating virtual environment for Python version 3.10 as an example)
- source ./venv/bin/activate
- pip3 install spyder (installing spyder using pip as an example)

### Start Spyder
- Open Terminal
- source ./venv/bin/activate
- export QT_QPA_PLATFORM=xcb (this setting needs to do if spyder application not open)
- spyder (type this command to start spyder which is installed in venv)
