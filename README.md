# Scripts for curl #

Contains a script for curl progress bar in terninal. Includes another script
to convert curl exit codes to curl status messages. Implemented in bash.
Common code that is often required by other scripts.
## How to install `curl-scripts` using apt-get ##

1\. Add [Whonix's Signing Key](https://www.whonix.org/wiki/Whonix_Signing_Key).

```
sudo apt-key --keyring /etc/apt/trusted.gpg.d/whonix.gpg adv --keyserver hkp://ipv4.pool.sks-keyservers.net:80 --recv-keys 916B8D99C38EAF5E8ADC7A2A8D66066A2EEACCDA
```

3\. Add Whonix's APT repository.

```
echo "deb http://deb.whonix.org buster main contrib non-free" | sudo tee /etc/apt/sources.list.d/whonix.list
```

4\. Update your package lists.

```
sudo apt-get update
```

5\. Install `curl-scripts`.

```
sudo apt-get install curl-scripts
```

## How to Build deb Package ##

Replace `apparmor-profile-torbrowser` with the actual name of this package with `curl-scripts` and see [instructions](https://www.whonix.org/wiki/Dev/Build_Documentation/apparmor-profile-torbrowser).

## Contact ##

* [Free Forum Support](https://forums.whonix.org)
* [Professional Support](https://www.whonix.org/wiki/Professional_Support)

## Donate ##

`curl-scripts` requires [donations](https://www.whonix.org/wiki/Donate) to stay alive!
