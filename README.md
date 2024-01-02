# Audio Synthesizer

## Overview

The Audio Synthesizer is a MATLAB-based application designed for audio processing and synthesis. It provides a user-friendly interface for loading, viewing, and editing audio files. The application includes a range of features such as grain selection, ADSR controls, tempo/pitch/volume adjustments, hum removal, and effects like delay and wah-wah. Users can also convolve two audio tracks and save the resulting sound.

## Main Features

### 1. Loading and Displaying Audio

- Load .wav audio files using `ui.getfile()` and `audioread()`.
- Display loaded audio with a spectrogram using the `axis_display()` function.

### 2. Audio Editing Section

- Two tabs for editing different audio tracks.
- Grain selection feature for selecting, playing, saving, and concatenating multiple grains.
- ADSR controls for adjusting attack, decay, sustain, and release percentages.

### 3. Tempo, Pitch, and Volume Controls

- Independent adjustment of tempo, pitch, and volume.
- Prevention of selecting percentages outside the valid audio range.

### 4. Audio Effects

- Option to flip audio upside down.
- Basic filtering through selecting and removing sections of the audio.
- Effects include delay and wah-wah with toggle switches.

### 5. Hum Removal

- User-friendly interface for selecting and cutting audio regions.
- Uses the `draw rectangle` function for easy selection.

### 6. Convolution

- Convolve two audio tracks.
- Post-convolution, users can continue to edit the resulting audio with pitch, tempo, volume, and ADSR controls.

### 7. Playback and Reset

- Play edited audio.
- Reset button to revert all changes.
- Stop button for halting audio playback.

### 8. Save

- Save the final convolved sound as "convolved.wav."
