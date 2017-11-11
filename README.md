# alfred-ffprobe
[Alfred 3][1] workflow to display an information about various video files.


## Installation

1) Install the [ffprobe][2] to you MacOS.

   - You could do it for example by using [Homebrew][3] and installing [ffmpeg package.][4]
   - ````brew install ffmpeg````
2) Install [alfred-ffprobe wokflow.][5]

## Usage

Select a video file in finder and invoke the alfred file actions <kbd>⌃﻿⌘\\</kbd>.

![Alfred actions screenshot](doc/images/alfred-actions.png?raw=true "")

Choose the `Analyze media file` in displayed menu and the information about selected video will be shown.

![alfred-ffprobe results screenshot](doc/images/alfred-ffprobe-results.png?raw=true "")

-------------------

From time to time, full results could be annoying, so there is another option just showing the results describing inner streams `Analyze media file (stream)`.

![Alfred actions screenshot](doc/images/alfred-actions-streams.png?raw=true "")

Output is much more well-arranged.

![alfred-ffprobe results screenshot](doc/images/alfred-ffprobe-results-streams.png?raw=true "")

[1]: https://www.alfredapp.com/
[2]: https://ffmpeg.org/ffprobe.html
[3]: https://brew.sh/
[4]: http://brewformulas.org/Ffmpeg
[5]: https://github.com/vookimedlo/alfred-ffprobe/releases/latest
