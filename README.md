# meow.mrrrp.kittens-Plymouth
The KDE startup animation with the same name lazily ported to Plymouth, featuring everyone's favorite, the boykisser.

<img width="2560" height="1440" alt="preview" src="https://github.com/user-attachments/assets/f0987b05-2917-4959-b1d2-81c8e9b69822" />
<sup> The preview was made from memory in Figma it looked something like that </sup>

## Installation
Download the release and extract the `meow.mrrrp.kittens` folder to `/usr/share/plymouth/themes`. Afterwards run `sudo plymouth-set-default-theme meow.mrrrp.kittens`.

## Notes
This was made for a 2K (2560x1440) display, on other screen sizes the progress bar will be wrong. To fix this open the `meow.mrrrp.kittens.plymouth` file inside the directory and edit the `ProgressBarWidth=2560` line, replacing the number with your screen width.

The animation is slower than the original, maybe there's a way to speed it up (feel free to pull request!).

This was really just made for me, I'm uploading it here in case anyone wants this animation on Plymouth.
