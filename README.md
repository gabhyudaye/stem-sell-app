# Stem Sell

A music toolkit for the Mac. Everything runs on your own computer: no account, no upload, no limits.

- **Split**: pull a song apart into vocals, instrumental, 4 or 6 stems (drums, bass, guitar, piano, other). Choose Quick, Balanced or Best quality.
- **Pitch & Speed**: change a song's key or tempo with a live preview.
- **Tempo & Key**: find the BPM, key and Camelot code.
- **Cut**: keep just one part, with fades.
- **Join**: merge songs with crossfades.
- **Record**: a voice recorder.
- **Karaoke**: remove a song's vocals, sing over it, and mix.
- **Library**: everything you've made.

## Download
Get **Stem-Sell-Mac.zip** from the [latest release](../../releases/latest).

Needs a Mac with an Apple chip (M1 or newer), about 3 GB of free space and an internet connection for the first setup.

1. Unzip it.
2. Double-click **RUNME.command** (if macOS blocks it, right-click it and choose Open). It installs ffmpeg, Python, the AI engine and the AI models, then opens Stem Sell. This takes several minutes.
3. Next time, just open **Stem Sell.app**. Keep it in the same folder as the `engine` folder that setup creates.

Results are saved in `Downloads/Stem Sell`.

## Please note
- Only split, cut or remix music you have the right to use.
- The app is not signed by Apple, which is why RUNME.command clears the "unidentified developer" warning for you.
- Separation quality: Best uses BS-RoFormer, one of the strongest open vocal models; Balanced uses MDX-Net; Quick uses Demucs.
- Windows is not supported.
