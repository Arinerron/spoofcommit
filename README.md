# About
Just a simple script to be executed in your local git repository folder to spoof commits as someone else.

# Installation
Either execute the below script, or clone the repository and `chmod +x spoofcommit` to make the file executable.
```
mkdir -p $HOME/bin/;wget https://raw.githubusercontent.com/Arinerron/spoofcommit/master/spoofcommit -O $HOME/bin/spoofcommit -q;chmod +x $HOME/bin/spoofcommit;echo "spoofcommit has been installed to $(echo \"$HOME/bin/spoofcommit\"). You can either add the folder to your PATH, or you can execute \". ~/bin/spoofcommit\" from the folder containing your git repository.";
```

# Usage
Rather than doing `git commit -m "example"`, execute the spoofcommit script with no parameters. It will ask you for the username (and in some cases, the email) and the commit message.
