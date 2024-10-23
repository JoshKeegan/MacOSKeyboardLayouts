# MacOS Keyboard Layouts

Custom keyboard layouts for MacOS, creating using [Ukelele](https://software.sil.org/ukelele/).

## Why?
Plugging my standard UK layout ISO Qwerty keyboard into a Macbook is frustrating because:
 - the default "British" layout it gets detected as is for Mac keyboards, so is wrong for several keys.
 - once you switch to "British - PC", it still has ` and \ swapped, which is the Mac layout for these keys.

The keyboard is a Ducky One 3 TKL, but I've spoken to others with the same issue on a variety of keyboards.

## Installation
 - Clone the repo (or download & extract it). Copy the bundle into either:
```zsh
# install for all users: /Library/Keyboard Layouts/
sudo cp -r UK\ ISO\ Swap\ \`\\.bundle /Library/Keyboard\ Layouts

# install for the current user only: ~/Library/Keyboard Layouts/
cp -r UK\ ISO\ Swap\ \`\\.bundle ~/Library/Keyboard\ Layouts
```

 - Restart.
- Go to System Settings > Keyboard
- Under "Text Input", select "Edit..." next to "Input Sources".
- Click + (bottom left)
- Add the custom layout
- 🎉
