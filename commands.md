# Command History and Descriptions

## Directory and File Operations
- `ls`: Lists the contents of the current directory.
- `mkdir practice`: Creates a new directory named "practice".
- `cd .ssh`: Changes directory to `.ssh`, a hidden folder typically used for SSH keys.
- `touch ffii.txt`: Creates an empty file named "ffii.txt".
- `vi ffii.txt`: Opens the "ffii.txt" file in the `vi` text editor.
- `cat id_rsa.pub`: Displays the contents of the `id_rsa.pub` file (SSH public key).

## SSH Operations
- `ssh-keygen`: Generates a new SSH key pair (public and private).
- `ssh -i id_rsa ubuntu@ec2-52-12-176-136.us-west-2.compute.amazonaws.com`: Connects to a remote EC2 instance using the private key `id_rsa`.

## Git Operations
- `git init`: Initializes a new Git repository in the current directory.
- `git add hello-dosto.txt`: Stages the `hello-dosto.txt` file for commit.
- `git commit -m "edited file hello-dosto.txt"`: Commits the staged changes with a message.
- `git log`: Shows the commit history of the repository.
- `git checkout -b dev`: Creates and switches to a new branch called `dev`.
- `git switch master`: Switches to the `master` branch.
- `git status`: Shows the current state of the working directory and the staging area.

## System Operations
- `pwd`: Prints the current working directory.
- `uname -s`: Displays the system name.
- `sudo passwd root`: Changes the root user's password.
