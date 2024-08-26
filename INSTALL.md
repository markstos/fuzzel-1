### [fuzzel](https://codeberg.org/dnkl/fuzzel)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/fuzzel.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/fuzzel/archive/master.zip) option and unzip them.

#### Activating theme

1. Navigate to/create config folder: `cd ~/.config/fuzzel/` or `mkdir -p ~/.config/fuzzel`
2. For Fuzzel >= 1.10:
   1. Create a themes directory: `mkdir ./themes`
   2. Copy the theme file `~/.config/fuzzel/themes/dracula.ini`
   3. Edit `~/.config/fuzzel/fuzzel.ini` to add `include=~/.config/fuzzel/themes/dracula.ini` in the main section scope of `fuzzel.ini`.
4. For Fuzzel < 1.10:  
   1. Copy/paste everything under `[colors]` to your `fuzzel.ini`.


