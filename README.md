# my_bashcommands

```
cd ~/.local/bin
git clone https://github.com/Andersgee/my_bashcommands.git
echo 'export PATH="$PATH:/home/andy/.local/bin/my_bashcommands"' >> ~/.bashrc
```

```
Usage: vlc-twitch name [quality] | dota2
Opens a twitch stream in vlc with livestreamer which must
be installed (pip install livestreamer).

  name:    what you would put in www.twitch.tv/name
  quality: default order is best,high,720p60,540p60,720p30,540p30,worst
             the available ones are displayed when opening a stream.
  dota2:   prints the 10 most popular dota2 streams at the moment.

```

```
Usage: ssh-connect name
A shorthand version of ssh using a name instead of adress.

  name: PC | RPI | localPC | localRPI | localRPI2

```
