# FundsXML training videos

Two short video series about [FundsXML](https://www.fundsxml.org), the open standard for fund data exchange:

- **FundsXML for business**: five films for business readers, management and project leads (5–8 min each)
- **FundsXML for developers**: eight films for developers, data teams and IT, shown in
  [FreeXmlToolkit](https://freexmltoolkit.org) (3–6 min each)

Watch them on the player page: <https://fundsxml.github.io/videos/>.

## What is here

| Path | Content |
|---|---|
| `en/NN-<id>.mp4` | the films, English, 1920×1080 |
| `en/NN-<id>.vtt` | subtitles (WebVTT) |
| `en/NN-<id>-chapters.vtt` | chapter marks |
| `posters/NN-<id>.jpg` | preview images |
| `videos.json` | the list of series and films with titles, descriptions, durations and chapters |
| `index.html` | the player page served by GitHub Pages |
| `wp-widget.html` | the same player as one HTML block for the fundsxml.org WordPress site |

Each series is also available as one film with chapters in the
[releases](https://github.com/fundsxml/videos/releases).

All examples use the fictional sample files of [fundsxml/examples](https://github.com/fundsxml/examples)
(`FundsXML_Files/4.2.9/realistic`): the companies, funds, securities and identifiers are made up.

## How the films are made

The films are generated with the video pipeline of FreeXmlToolkit (`scripts/make-video.py`): storyboards with the
narration, speech from a local text-to-speech model, the picture from the real application driven by a scenario,
and the cut by ffmpeg. `scripts/publish-videos.py` there writes the contents of this repository.

## Disclaimer

These videos are for training purposes only and are not legal, regulatory or investment advice. The official
FundsXML documentation and the applicable regulations are binding. Narration and editing are AI-generated; the
videos show the real application.

## License

The videos, subtitles, chapters and preview images are licensed under
[Creative Commons Attribution 4.0 International](LICENSE-CC-BY-4.0.txt) (CC BY 4.0). The player code
(`index.html`, `wp-widget.html`) is licensed under the [Apache License 2.0](LICENSE-APACHE-2.0.txt). The FundsXML
name and logo belong to FundsXML.
