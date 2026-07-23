# asterisk-core-sounds-uk
Core Asterisk Sounds in Ukrainian

See [core-sounds-uk.txt](core-sounds-uk.txt) for the full list of prompts and what each one says.

## Installing into FreePBX

A `.deb` package is built from this repo and published to [vladonv/apt](https://github.com/vladonv/apt):

```
apt-get install asterisk-core-sounds-uk
```

It installs into `/var/lib/asterisk/sounds/uk_UA`. In FreePBX, register `uk_UA` as a custom Sound Language (Admin -> Sound Languages) if it isn't already, then select it wherever a Sound Language can be chosen.
