# Shell Configurations Backup

This repository holds a collection of personal configuration files for various shell environments, including fish, bash, and zsh. The purpose of this repository is to provide an easy way to back up, share, restore or apply shell configurations.

## Shells Supported 

- **Fish**: Configuration files for the Fish shell.
- **Bash**: Configuration files for the Bash shell.
- **Zsh**: Configuration files for the Zsh shell.

## Installation

1. To use these configurations, follow these steps:

   ```bash
   git clone https://github.com/mizdrake7/shell_configs.git
   cd shell_configs 
   cp fish/config.fish ~/.config/fish/config.fish
   cp bash/.bashrc ~/.bashrc
   cp zsh/.zshrc ~/.zshrc
   ```

2. Using Custom Configuration Names:

   If you are using custom configuration file names or locations, ensure that you load them properly by adding the appropriate commands to your shell's startup file:
   
   fish : If your custom configuration file is named my_config.fish, load it by adding this line to your config.fish:

   ```bash
   source ~/.config/fish/my_config.fish
   ```
   
   bash : For a custom .bashrc file named .my_bashrc, load it by adding this line to your existing .bashrc or .bash_profile:

   ```bash
   if [ -f ~/.my_bashrc ]; then
    source ~/.my_bashrc
   fi
   ```
   
   zsh : For a custom .zshrc file named .my_zshrc, ensure you load it by adding this line to your .zshrc

   ```bash
   source ~/.my_zshrc
   ```

## Acknowledgments
Thanks to the communities behind fish, bash, and zsh for their incredible work in creating these powerful shell environments.
Feel free to add your perosnal configs tweaks and configurations.
