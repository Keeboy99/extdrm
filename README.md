# extdrm

A tool for decrypting extdrm encrypted filesystems

# Usage

```
extdrm utility

Usage:
  extdrm [command]

Available Commands:
  dump        Decrypt the contents of an encrypted extdrm filesystem
  help        Help about any command
  presets     List built-in presets
  verify      Verify the integrity of a filesystem dump

Flags:
  -h, --help   help for extdrm

Use "extdrm [command] --help" for more information about a command.
```

To dump the contents of an encrypted filesystem, simply run `extdrm dump SOURCE DESTINATION`.

After a successful dump, you may perform a file check by running `extdrm verify DESTINATION`.

## Presets

Presets are responsible for controlling the decryption process. The dumper comes included with several built-in presets. <br>
The dumper will try to automatically determine the correct preset to use, so most users won't have to worry about manually specifying one.

List of built-in presets and their respective games:

### Arcade

- drs: DANCERUSH STARDOM
- iidx: beatmania IIDX 30 RESIDENT ~ current
- sdvx: SOUND VOLTEX VIVID WAVE ~ current
- dance_around: DANCE aROUND
- polaris: Polaris Chord

### コナステ/Konasute:

- eac/bonga: Bombergirl
- eac/ddr: DanceDanceRevolution GRAND PRIX
- eac/gitadora: GITADORA
- eac/infinitas_2020: beatmania IIDX INFINITAS 2020
- eac/infinitas_2020_cache: beatmania IIDX INFINITAS 2020 (cache)
- eac/infinitas_2024: beatmania IIDX INFINITAS 2024
- eac/infinitas_2024_cache: beatmania IIDX INFINITAS 2024 (cache)
- eac/nost: NOSTALGIA
- eac/popn: pop'n music Lively
- eac/sdvx: SOUND VOLTEX EXCEED GEAR
