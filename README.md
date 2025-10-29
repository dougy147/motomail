Deploy a secure self-hosted mailserver at the speed of a motorcycle.

Run `motomail` on a fresh Debian 13:

```console
$ ./motomail
```

To add domains on same server:

```console
$ ./motomail --add-domain
```

# READ THIS

- Debian 13 **required** (for other distros, prepare for tweaks)
- add `--reuse-key` to certbot (e.g. `systemctl edit --full certbot.service`) to avoid DANE's troubles when renewing certificates
- mail users need an account on the system (i.e. no sql database)

# About

`motomail` is an interactive script to setup a secure self-hosted mailserver.
By secure, we mean it follows modern internet standards as prescribed by [internet.nl](https://internet.nl/).
It improves and borrows to [`emailwiz`](https://github.com/LukeSmithxyz/emailwiz) script.

```txt
   [v]  @
  =m++_/-|>
   (o)t\_(o)
```
