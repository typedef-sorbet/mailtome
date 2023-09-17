## mailtome -- For when a flash drive is too much work.

`mailtome` takes a path as an argument, and sends the data contained within that file to you via email, for use on another device.

`mailtome` expects an INI-formatted file at `~/.config/mailtome.conf` containing the following data:

```ini
user=<base64-encoded email address>
pass=<base64-encoded password/app password; see https://support.google.com/accounts/answer/185833?hl=en>
email=<your email address>
```
