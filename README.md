# myssh
A simple Python program to manage SSH connections.

## Requirements
Python 3

## How to run?
First clone the repo and make the file executable:
```
git clone git@github.com:sinahamedheidari/myssh.git
cd myssh
chmod +x myssh
```

There is only one file; myssh

Open the file and edit the ```server_list``` dictionary. There are some dummy server data.

To display the information of all servers:
```
./myssh --list
```
To connect via server ID:
```
./myssh --id <server_ID>
```

To get help:
```
./myssh --help
```
