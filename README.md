![Example EMVizLogo.png](EMVizLogo.png)

EMViz (Early Music Visualization) provides built-in pattern recognition for symbolic music based on a contour recursion algorithm by Carter-Enyi (2016) producing visualizations of musical form using arc diagrams, as proposed by Wattenberg (2002). The algorithm brings together contour theory (Morris 1987, Quinn 1996, Schultz 2013) with studies of melodic
accent (Thomassen 1982, Huron 2006). Symbolic music data (.midi, .xml) from various sources (including ELVIS at McGill and the Yale Classical Archives Corpus) may be imported, analyzed and visualized in a matter of minutes. Arc diagram visualizations in the supplemental materials include music from the Liber Usualis, Josquin des Prez and J. S. Bach.

## Getting Started

Mac OSX version:
https://morehousecollege.box.com/s/3ziy19h8n36l54oza5fcesx2f9z7y2yg

Windows version:
https://morehousecollege.box.com/s/cd2t5kb5xt4e3f7zsd0zcnbat2e9b1vw

Or github repository:
https://github.com/carterenyi/emviz

### Prerequisites

If you have MATLAB 2017b, you will not need to install MATLAB Runtime and may also run individual scripts (source code) from the github repository.

### Installing

Detailed instructions for installation:
1. You will need a web connection for the entire installation because MATLAB Runtime
(also free) will also be downloaded and installed when you run the application installer
2. Download the entire folder at the appropriate link above
3. Find the “AppInstaller” folder or zip file and double-click it, then double-click
“MyApplicationInstall_web” (.exe for Windows and .app for Mac); Mac will unzip
revealing a “test” folder (which has the MyApplicationInstall_web.app inside); Windows
may also ask you to expand the files before installing (if so, you will need to double-click
the installer again after this unpacking)
4. Because this software is not from an “App Store”, you will likely need to override
some security preferences after expanding/unzipping and clicking on the .app or .exe, to
do this right-click or control-click and select “Open” on Mac or “Run as administrator”
on Windows
5. The actual installation process (which requires an internet connection) may take 5 – 20
minutes depending on the download speed of your internet connection (it is downloading
MATLAB Runtime so your computer can interpret the code for the algorithm and GUI)

## Running the tests

MIDI files for testing are included at the link above. You should be able to produce the images in:
https://github.com/carterenyi/emviz/blob/master/paper.md

## Deployment

Details for installation on a live system are above.

## Built With

MATLAB 2017b

## Contributing

Please read https://github.com/carterenyi/emviz/blob/master/contributing.md for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Aaron Carter-Enyi** <carterenyi@gmail.com>

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Inspired by Martin Wattenberg's Shape of Song and the phonology of Niger-Congo (African) tone languages.
