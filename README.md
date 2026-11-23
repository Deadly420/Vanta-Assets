# Vanta Assets

Files the Vanta client downloads on first run into `%APPDATA%\Vanta Client`, keeping the same folders:

- `Assets/vanta_logo.png`: home-screen logo
- `Assets/vanta_v.png`: menu logo mark
- `CustomSounds/Enable.wav`, `CustomSounds/Disable.wav`: Custom toggle sounds
- `Assets/icons-1.bin`: interface icons (Lucide, see `LUCIDE_LICENSE`)
- `Assets/logo-1.bin`: the logo as meshes
- `Assets/shaders-1.bin`: compiled outline shaders

A replaced image or sound is kept: the client only downloads those when missing. The `.bin`
files are pinned by SHA-256 in the client. Never change one in place; add the next number.

`Art/` holds the sources the generators use; the client does not download it.
