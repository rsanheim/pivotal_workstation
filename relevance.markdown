Xcode 4.2 apparently has a very unfriendly version of GCC, which not
only breaks many installs of Ruby but also breaks many homebrew
packages.

The solution for now is to stick with Xcode 4.1, which you can download
from here:

  https://developer.apple.com/downloads/download.action?path=Developer_Tools/xcode_4.1_for_lion/xcode_4.1_for_lion.dmg

If you happen to have 4.2 already, you can uninstall it with the
following:

    sudo /Developer/Library/uninstall-devtools --mode=all
