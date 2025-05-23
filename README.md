# WSL-notes
Notes on working with Windows Subsystem for Linux

# Password change
```cmd
Open cmd.exe
Type wsl -u root
Type passwd username and change the password
Type exit
Type wsl
Type sudo echo hi to confirm the new password works.
```
```bash
Installing Miniconda on WSL
Here's how to install Miniconda on Windows Subsystem for Linux (WSL):

Open your WSL terminal
Download the Miniconda installer:
bash wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh

Make the installer executable:
bash chmod +x Miniconda3-latest-Linux-x86_64.sh

Run the installer:
bash ./Miniconda3-latest-Linux-x86_64.sh

Follow the prompts:

Accept the license agreement
Confirm the installation location (or change it if needed)
When asked if you want to initialize Miniconda3, type "yes"


Activate the installation:
bash source ~/.bashrc

Verify the installation:
bash conda --version

import torch
print(torch.cuda.is_available())
```
