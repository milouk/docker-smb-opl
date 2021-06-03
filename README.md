## Dockerized Samba Server for Open PlayStation Loader

OPL can stream backed up games from SMB. Although the process of creating a share
and enabling smb is straightforward for Windows, in MacOS or Linux it is not.

Hence, the reason for creating this repo. To set up an SMB server for streaming
games on your PS2 do the following.


On your PC

1. You need to export a variable with the path of your share. You can do this by typing `export SHARE_PATH=/my/path/to/PS2SMB/`
2. You then type `docker-compose up`


On your PS2

1. As your share enter `PS2SMB` (this is important)
2. As a username enter `guest`
3. Leave password empty

Enjoy!
