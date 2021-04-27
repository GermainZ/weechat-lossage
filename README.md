# Description:
Inspired by Emacs's `view-lossage`, this script displays a history of the last
keystrokes you performed and the commands invoked, if any.

For consistency, the keystrokes displayed follow the same format as WeeChat's
`meta-k /input grab_key_command`.

# Download:
weechat-lossage is available in the WeeChat scripts repo. You can install it by
running the following command:

    /script install lossage.py

The version on GitHub may be more recent. You can install it from the shell as
follows:

    cd ~/.weechat/python/
    wget 'https://github.com/GermainZ/weechat-lossage/raw/master/lossage.py'
    cd autoload/
    ln -s ../lossage.py .

If you prefer to clone the git repo (allowing you to easily update it), you can
do the following instead:

    git clone 'https://github.com/GermainZ/weechat-lossage.git'
    ln -s /path/to/git/repo/vimode.py ~/.weechat/python/autoload/lossage.py


# Screenshot:
![Screenshot](screenshot.png?raw=true "Screenshot")

# Usage:
The script starts recording keystrokes when it is loaded.
To invoke it, execute `/lossage`.

# Support:
Please report any issues using the [GitHub issue tracker][1]. Also feel free to
suggest new features that you need.

You can contact me on irc.freenode.net in #weechat or via a query (nickname:
GermainZ).

[1]: https://github.com/GermainZ/weechat-lossage/commits/master
[2]: https://github.com/GermainZ/weechat-lossage/issues/new
