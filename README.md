# ScriptCollection

Just a little bash script collection that makes my life easier during my daily tasks in the DevOps and Linux admin world.

## Scripts Included
- docker-armaggedon: Erases EVERYTHING on docker.
- docker-ssh: ssh-style terminal to a docker container bash
- tfcreate: used to recreate the terraform environment in case of a terraform error when you make changes to the terraform code.
- pubip: checks for VPN network adapters and displays your public IP and country code.

## Usage

Copy and paste:
```BASH
git clone https://github.com/JohnMorgan1234/ScriptCollection.git
cd ScriptCollection
#Change permissions to all files but not to README.md
find . -type f ! -name 'README.md' -exec chmod +x {} +
#Copy all files ignoring README.md to /usr/local/bin
find . ! -name 'README.md' -exec sudo cp -R {} /usr/local/bin \;

```
