
## Installation in Termux
> Update Termux repositories.
```bash
yes|pkg update && yes|pkg upgrade
```
> Grant storage permissions to Termux.
```bash
termux-setup-storage
```
> Install "git" version control software.
```bash
yes|pkg install git
```
> Clone github repository.
```bash
git clone https://github.com/Darkmux/cyberspy.git
```
> Access the cloned "cyberspy" folder.
```bash
cd cyberspy
```
> Grant execute permissions to all files with extension (.sh).
```bash
chmod 777 *.sh
```
> Run the installer.
```bash
bash cyberspy.sh
```
## New Commands Available
> The main command is `spy` which is used along with its arguments for it to work properly:
## Arguments Available
> Shows a help menu on the use of cyberspy in the terminal.
```bash
spy help
```
> Shows the list of tools or banners available to use and install.
```bash
spy list <tools|banners|prompts>
```
> Find and update CyberSpy to its latest version.  (Run it whenever they enter the terminal).
```bash
spy update
```
> Completely uninstall CyberSpy and go back to the default Termux (only use it if you don't like cyberspy).
```bash
spy uninstall
```
> Changes the size of the banner depending on the specified argument.  (It is recommended to adapt it to your font size in Termux).
```bash
spy style <banner|prompt>
```
> Installs the tool specified as an argument.
```bash
spy install <tool>
```
> Removes the tool specified as an argument.
```bash
spy remove <tool>
```
> Reinstall the tool specified as argument.
```bash
spy reinstall <tool>
