# net-merge test build: phone hotspots

Unofficial, unsigned Windows test build of the `phone-saver` branch (commit a1d2f99). Not a release.

- `net-merge-setup-0.3.8-phone-saver.exe`: installer (64-bit)
- `net-merge-0.3.8-phone-saver-windows-portable.zip`: portable zip, no install

What it does with an iPhone hotspot:

- Always: checks the phone for internet less often, keeps idle connections on it alive less often, and
  keeps single connections off it when your other connection is at least as fast. No speed is lost.
- Only if you tick *Cool down phone hotspots* in the tray menu: after 3 minutes of heavy use the phone
  is held at 20 Mbit/s until it has had a rest. The tick is remembered.

Windows will warn that it is unsigned: click *More info*, then *Run anyway*.

SHA-256:

```
f8676e147e7da081e9889c9c482895884ad1a2c16d24de7f00a71a9992fa90ff  net-merge-setup-0.3.8-phone-saver.exe
0a857d764de2c7b22cb1308f122171834c7cf817b0a3dbcbc68a5baccb656591  net-merge-0.3.8-phone-saver-windows-portable.zip
```
