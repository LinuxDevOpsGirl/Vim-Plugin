Install Process:

Check prerequisites

    git --version

The correct result✅：

    git version 2.12.2

    lua -v

The correct result✅：

    Lua 5.3.4 Copyright (C) 1994-2017 Lua.org, PUC-Rio

Notice: Different Operating system may has different names of lua. For example, lua or lua53 or lua52.

    python -V

The correct result✅：

    Python 3.6.0

    vim

The correct result✅：

    You can see vim in your terminal

Notice: You have to install them by corresponding package manager. For expample:

    Debian/Ubuntu:

        sudo apt-get install git

    Fedora:

        sudo dnf install git

    CentOS/RHEL:

        sudo yum install git

    Arch

        sudo pacman -S git

Start to install

    Back up your own .vimrc. Just in case you don't like SpaceVim

    Execute: curl -sLf https://spacevim.org/install.sh | bash

    Launch: vim

After finishing downloading plugins, you installed SpaceVim successfully!

    Check whether your vim has +Lua and +python feature. Use vim --version | grep -E 'lua|python' to check out:
