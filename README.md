# Max for Live Vectorscope

Monitor your stereo image in Ableton Live.

![Vectorscope Screenshot](https://i.imgur.com/kuXFxu0.gif)

## What is a Vectorscope?

A vectorscope visualizes the relationship between two audio channels (left and right) on an X-Y display. It's an essential tool for:
- Monitoring stereo width
- Checking phase correlation
- Analyzing stereo imaging and balance
- Identifying mono compatibility issues

## Features

- Clean, modern interface with minimal CPU usage
- Real-time display of stereo field visualization
- Follows Ableton Live's color theme automatically
- Phase correlation measurement (vertical meter)
- Balance indication (horizontal meter)
- Transparent audio pass-through (no coloration)
- Lightweight with minimal impact on CPU

## Installation

1. Download the latest release from the [releases page](https://github.com/ogtega/m4l_vectorscope/releases)
2. Drag the `Vectorscope.amxd` device into Ableton Live's browser under "Max for Live/Audio Effects"
   - Or place in your Live User Library: `~/Music/Ableton/User Library/Presets/Audio Effects/Max Audio Effect/`

## Usage

1. Drop the Vectorscope device on any audio track, return track or the master channel
2. The display shows the stereo field representation:
   - Vertical movement indicates opposite phase content
   - Horizontal movement shows panning/balance
   - Round shape indicates well-correlated audio
   - Wide horizontal shape indicates stereo content
   - Diagonal line (45°) indicates phase issues

### Reading the Vectorscope

- **Mono signals**: Appear as a vertical line
- **Stereo signals**: Create various patterns depending on the content
- **Phase correlation**: When signals are out of phase, the pattern extends horizontally
- **Balance indicator**: Shows the relative strength between left and right channels

## Requirements

- Ableton Live 10.1 or later
- Max for Live
- Max 8.0 or later

## Development

This device was built using:
- Max 8
- [Jitter](https://cycling74.com/products/max) for graphics processing
- Gen~ for DSP calculations

## License

This project is released under the MIT License. See the LICENSE file for details.

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues to improve the device.

## Acknowledgements

Thanks to the Max/MSP community for inspiration and resources on building audio visualization tools.

---

Made with ♥ by Tes
