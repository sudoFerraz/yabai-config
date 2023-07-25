# Yabai and Skhd Config

This repository contains my standalone Yabai and Skhd configurations.

NOTE: Yabai requires System Integrity Protection to be disabled to work properly. See [here](https://github.com/koekeishiya/yabai/wiki/Disabling-System-Integrity-Protection) for more information.
NOTE: For macOS Big Sur and above, scripting additions needs elevated privileges to work properly. See [here](<https://github.com/koekeishiya/yabai/wiki/Installing-yabai-(latest-release)#macos-big-sur---automatically-load-scripting-addition-on-startup>) for more information.


```sh
# Remove previous links
$ rm -f "${HOME}"/.{yabai,skhd}rc

# Install configs
$ git clone https://github.com/sudoferraz/yabai-config.git "${HOME}"/.config/yabai
$ ln -s "${HOME}/.config/yabai/yabairc" "${HOME}/.yabairc"
$ ln -s "${HOME}/.config/yabai/skhdrc" "${HOME}/.skhdrc"
```

