# sublime
Share sublime settings across machines

# OSX

- Install Package Control
- Quit Sublime
- git clone git@github.com:mturilli/sublime.git ~/.sublimeconf
- mv -rp ~/Library/Application Support/Sublime Text 3/Packages/User ~/Library/Application Support/Sublime Text 3/Packages/User.OLD
- ln -s ~/.sublimeconf ~/Library/Application Support/Sublime Text 3/Packages/User
- subl
