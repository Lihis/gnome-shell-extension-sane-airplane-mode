# Sane Airplane Mode

Make airplane mode sane again! This extension gives you better control over the airplane mode. Ot at least it is my attemt so make a utterly broken airplane mode implemetation somewhat sane to handle.


## Known limitations

 - When in airplane mode, turning on Bluetooth is indistinguishable from turning off airplane mode and will be treated accordingly.
 - When choosing not to enable both Bluetooth and Wi-Fi airplane mode might get reactivated. Altough this behaviour (at least on my machine) is only observed the first time disabling airplane mode, since then it works perfectly well.


## Installation

Installation via git is performed by cloning the repo into your local gnome-shell extensions directory (usually ~/.local/share/gnome-shell/extensions/):

    $ git clone https://github.com/xKippi/gnome-shell-extension-sane-airplane-mode.git <extensions-dir>/sane-airplane-mode@kippi

After cloning the repo, the extension is practically installed yet disabled. In order to enable it, find the extension titled 'Sane Airplane Mode', in the 'Extensions' application and turn it 'On'.
You may need to restart the GNOME shell (<kbd>Alt</kbd>+<kbd>F2</kbd> and insert 'r' in the prompt) for the extension to be listed there.