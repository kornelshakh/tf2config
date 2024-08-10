# tf2config
`-dxlevel 90 -novid -nojoy -nosteamcontroller -nohltv -particles 1 -precachefontchars -w 1920 -h 1080 +exec preloader.cfg`

- `-dxlevel 90` — Sets DirectX level to 9.0
- `-novid` — Skips the intro video
- `-nojoy` — Disables joystick support
- `-nosteamcontroller` — Disables Steam Controller support
- `-nohltv` — Disables SourceTV
- `-particles 1` — Reduces particle detail
- `-precachefontchars` — Preloads all font characters to reduce stuttering
- `-w 1920 -h 1080` — Sets resolution to 1920x1080
- `+exec preloader.cfg` — Runs the `preloader.cfg` file on launch (needed for the preloader in `tf\custom`)
