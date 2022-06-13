# orange_stomp
set of scripts to make orange pi one plus to preform as headless guitar+vocal processor, that automatically starts after power on without any user interaction. no screen or any input device needed, the button for changing presets is optional. it's mostly guitarix-based. presets is up to you - you know what you need. scripts are simple, nothing is auto-detected, so they require editing for your needs - presets names, inputs, plugin params etc.. polling is used for button, if you managed to catch interrupts on orange pi one plus - please let me know. these scripts are tested with armbian, but most likely usable with any systemd-based distro with minor changes

Look at this ansible playbook, at least you need dbus config from there, also you may want webgui, but I used it just as reference https://gist.github.com/OddBloke/bc0c13f7b65095ae52ed23d94e659fbf

hardware pull up resistor is strongly(!) recommended, if you know why software-configurable pull up leaves input unstable even on short lines - please contact me

audio interface used in my setup is emu 0202 usb
