
Deploy a secure self-hosted mailserver with a single script.

```txt
   [v]  @        _  _ o      _  _ a
  =m++_/-|>     / \/ \ t    / \/ \ i
   (o)t\_(o)   /_/\/\_\ o  /_/\/\_\ l 
```

# Quick deploy

Run this on your Debian 13 VPS:

```console
$ wget 'https://gitlab.com/dougy147/motomail/-/raw/master/motomail'
$ chmod +x motomail
$ ./motomail
```

To add domains on same server:

```console
$ ./motomail --add-domain
```

# ABOUT

`motomail` is an interactive script to setup a secure self-hosted mailserver.
By secure, we mean it follows modern internet standards as prescribed by [internet.nl](https://internet.nl/).
It improves and borrows to [`emailwiz`](https://github.com/LukeSmithxyz/emailwiz) script.
