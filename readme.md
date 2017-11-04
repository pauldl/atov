# AtoV

`atov` is an audio-to-video generator. Its intent is to create a video
representation of a multi-track audio file, specifically for talk recordings
where each track is a unique voice.

>>> TODO: example gif w/ waveform

## Usage

`atov init`: Create a new atov project.

`atov collect <image>`: Collect assets for the project.

`atov generate`: Create the compiled video using the collected tracks and
images.