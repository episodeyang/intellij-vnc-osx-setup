# intellij-vnc-osx-setup

This is a working setup for getting `meta + D` and other mac key combinations
to work with an IntelliJ IDE in a remote linux box. There are a number of things
that have to happen once for it to work.

## Linux Box

Make sure you set: `Meta is mapped to Win`. Otherwise the multi-key sequence
with `meta + <ascii>` would not work.

I am not sure why this is the case, but if you know please let me know.

### VNC setup

## Mac Host

### SSH Tunnel

### Karabiner

You need what is called a `complex rule`. The final (barebone and clean)
karabiner setup is in [./karabiner_configurations/karabiner.json](./karabiner_configurations/karabiner.json)
under this repository. In OSX, this file is located at

> /Users/<your-username>/.config/karabiner

You can look at that file and copy the parts appropriate.

### TigerVNC

In case you are a CJK IME user (like me), you need to **make sure** that
you are using the US input method. This is an issue with the TigerVNC.
Using just the US input method works very well.
