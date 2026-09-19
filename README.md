# RICHMACK Audio CLI

Local text-to-audio CLI using Piper and SoX.

Features include the Alan British Piper voice, sentence-by-sentence rendering,
48 kHz stereo processing, 180 Hz body tone, 180/190 Hz stereo tone pair,
pink noise, deliberate pacing, and 24-bit WAV output.

## Usage

    richmack-audio script.txt
    richmack-audio --preview script.txt preview.wav
    richmack-audio --slow script.txt
    richmack-audio --fast script.txt
    richmack-audio --voice-only script.txt voice.wav

Generated audio and Piper models are excluded from Git.
