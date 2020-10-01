# Tracku : Search username in CLI


## Installation

```console
# clone the repo
$ git clone https://github.com/pradyyadav/tracku.git

# change the working directory to sherlock
$ cd tracku

# install the requirements
$ python3 -m pip install -r requirements.txt
```

## Finding Usernames

To search for only one user:
```
python3 tracku user123
```

To search for more than one user:
```
python3 tracku user1 user2 user3
```

Accounts found will be stored in an individual text file with the corresponding username (e.g ```user123.txt```).


## Thanks to 

[Sherlock](https://github.com/sherlock-project/sherlock)
