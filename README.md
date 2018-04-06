# gentoo-overlay
Packages that I need and either don't exist or maintainers don't update frequently enough.

To add this to your list of overlays, as root, run the following

```
# Download and save this repo xml to /etc/layman/overlays/
curl -o /etc/layman/overlays/camwheel.xml https://raw.githubusercontent.com/camwheeler/gentoo-overlay/master/camwheel.xml

# Add my overlay to layman
layman -a camwheel

# Sync camwheel layman overlays
layman -s camwheel

# or sync all layman overlays
layman -S
```

If you don't have layman setup on your machine please read this: https://www.gentoo.org/proj/en/overlays/userguide.xml

----------
