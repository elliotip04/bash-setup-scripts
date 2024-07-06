# bash-setup-scripts

This repository contains configuration scripts for setting up your shell environment, including `.bashrc` and `.bash_profile`. These scripts ensure that your SSH agent is properly started and SSH keys are loaded each time you start a new shell session.

## Repository Contents

- [.bash_profile](.bash_profile): Configuration script that runs for login shells.
- [.bashrc](.bashrc): Configuration script that runs for interactive non-login shells.

## Note

This assumes you already have a `.ssh` directory set up with your repository, your private key, and public key. If you haven't set this up yet, you can follow these guides to generate a new SSH key and add it to your SSH agent:

- [Generating a new SSH key and adding it to the SSH agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [Adding a new SSH key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)


## Usage

### Setting Up

1. **Clone the repository to your local machine**

   ```sh
   git clone git@github.com:elliotip04/bash-setup-scripts.git

2. **Go to your home directory**
   ```sh
   cd ~

3. **Create the .bashrc file**

   ```sh
   nano .bashrc
   
4. **Copy and paste the provided [.bashrc](.bashrc) content into the file.**

5. **Create the .bash_profile file**
   
   ```sh
   nano .bash_profile

6. **Copy and paste the provided [.bash_profile](.bash_profile) content into the file**
