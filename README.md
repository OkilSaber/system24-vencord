# system24 bloodmoon for vencord

[refact0r's system24](https://github.com/refact0r/system24) Discord theme with the BloodMoon colors from the spicetify [text](https://github.com/spicetify/spicetify-themes/tree/master/text) theme, on a true black (amoled) background.

Differences from system24:

- amoled palette: true black panels, dark red borders that turn bright red on hover
- text in regular weight with normal letter spacing (system24 uses 300 and -0.05ch), easier to read
- softened text colors and readable muted text and panel labels (contrast >= 4.5:1)
- fixes the missing bottom border on title bars drawn as panels (friends, message requests, nitro, vc chat, threads)

## Install

Online theme: in Discord, **Settings → Vencord → Themes → Online Themes**, add:

```
https://raw.githubusercontent.com/OkilSaber/system24-vencord/main/system24-bloodmoon.theme.css
```

Local theme: copy `system24-bloodmoon.theme.css` into the Vencord themes folder and enable it under **Local Themes**.

The file imports system24 itself, so remove the system24 online link if you had it.

## Customize

All colors are CSS variables in the `:root` block; for a lighter background instead of true black, set `--bg-4` to `#1a1416` and `--bg-3` to `#221a1c`.

## Credits

[system24](https://github.com/refact0r/system24) by refact0r, MIT.
