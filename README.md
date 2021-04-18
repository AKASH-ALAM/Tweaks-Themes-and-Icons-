# Tweaks-Themes-and-Icons-

For Ubuntu gnome desktop Environment.

### How to Install and Change GNOME Theme in Linux


### Install gnome-tweak-tool
Open the terminal application and type the following :

       sudo apt update
       sudo apt install gnome-tweak-tool

I also recommend that you install the following package:

       sudo apt install gnome-shell-extensions
       
By changing your GNOME theme, you can give your Linux desktop a brand-new look and feel.

In this tutorial, I’ll show you how to install new themes on a Linux system running GNOME desktop environment.

There are two aspects of GNOME theme:

* Application theme: changes the appearance of the application windows
* Shell theme: changes the shell elements like the top panel, system tray, message tray and notifications
I’ll show you how to change both aspects of a GNOME theme in this tutorial.

Installing themes in GNOME
Before you go on downloading the themes, you should make sure of a few things as prerequisite.

There are two places the themes files can be placed:

* ~/.themes : You may have to create this folder in your home directory if it doesn’t exist. The themes placed here will be available only to you (the logged in user)
* /usr/share/themes: The themes put in this folder will be available to all the users on your system. You need to be root to put files in this folder.

Normally, I suggest going with the former one which is ~/themes.

To do that go to your Home diectory. Press Ctrl+H to show hidden files and folders. If you don’t see the .themes directory, create it.

Alternatively, use this command in the terminal to create this directory:

       mkdir ~/.themes

The next thing you should make sure of is to have GNOME Tweaks tool installed on your system otherwise you won’t be able to change the theme. You can use your distribution’s software center or package manager to install it.

### Download GNOME themes
First thing first, you need to get some good GNOME themes. You can find plenty on the Gnome-look website.

[Get Themes From Gnome-look](https://www.gnome-look.org/)

If you want suggestions, please have a look of our [list of the best GNOME themes](https://itsfoss.com/best-gtk-themes/)

Extract the downloaded theme file. Copy the folder and paste it in the .themes folder of your home directory (that you had created earlier).

### Change GNOME theme
Once you have installed new themes, it is time to see how to use this new GNOME theme. You have GNOME Tweaks tool installed for this purpose.

Press Super key (Windows key) and search for GNOME Tweak Tool. Click on it to open it.

Now under Appearance section, you should see the options to change icons, applications and shell themes.

You’ll see that while it is easy to change the Applications theme, the Shell theme has a warning sign in front of it and you cannot change it.

Don’t worry. This can be ‘fixed’. Let me show you how to do it in the next section.

### Troubleshoot: Not able to select GNOME Shell theme in GNOME Tweaks tool

If you see an exclamation mark and you can not select themes in it, you need to an exra step.

Don’t worry. It’s not a big deal. You need to [install GNOME Shell Extensions](https://itsfoss.com/gnome-shell-extensions/) to fix this issue. Use the following command in the terminal:

        sudo apt install gnome-shell-extensions

After installing the extensions, go to Extensions->User Themes and turn it on.

In case the User Theme does not appear after installing the extension, then try logging out or rebooting.

Also, in case if the GNOME Shell extension does not work for you at all, you can try out the [Gnome Shell Browser extension](https://extensions.gnome.org/)

Once you enable the extension, click on the User themes and toggle on the off button, and you are all done. Also, to know more about the GNOME extension, you can have a look at the [How to Use GNOME Shell Extensions guide](https://itsfoss.com/gnome-shell-extensions/)

Now, you should be able to install the themes as described earlier.

The theme change should reflect immediately. If you do not see the theme changes immediately, press Alt+F2 key or FN+ALT+F2 key.

It will open a command box. Just type ‘r’ in it. This will restart the GNOME shell and the selected theme should be applied.

You can get plenty of GNOME Shell themes from Gnome-look website. But beware that not all themes might be compatible with your version of GNOME Shell.

I hope this helps you to easily and correctly install themes in GNOME. Any questions or suggestions are always welcomed.
