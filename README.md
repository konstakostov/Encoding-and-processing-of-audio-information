# Encoding and processing of audio information

This repository will contain information about the "*Encoding and Processing of Audio Information*" laboratory exercises.

---

## Required Software
#### To complete the exercises, you have the following options:

### Option 01:
#### Utilize MyBinder.org to access an online Jupyter environment without installation or registration

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/konstakostov/Encoding-and-processing-of-audio-information/HEAD)

---

### Option 02:
#### Install Python, IDE, and external libraries on your local machine. Recommended Python versions and IDE's are:
- <a href="https://www.python.org/downloads/">Python 3.9 or higher</a>
	- <a href="https://realpython.com/installing-python/#windows-how-to-check-or-get-python">How to install Python</a> 
- <a href="https://ffmpeg.org/download.html">FFmpeg</a>
	- <a href="https://www.hostinger.com/tutorials/how-to-install-ffmpeg">How to install FFmpeg</a>
- IDE (Choose one of the following):
	- <a href="https://code.visualstudio.com">Visual Studio Code (VS Code)</a>
		- <a href="https://code.visualstudio.com/docs/setup/setup-overview">How to install VS Code</a> 
	- <a href="https://vscodium.com">VSCodium</a>
		- The installation manual is at the bottom of the official page.
	- <a href="https://www.jetbrains.com/pycharm/download/">PyCharm (Community Edition)</a>
		- <a href="https://www.jetbrains.com/help/pycharm/installation-guide.html#silent">How to install PyCharm (Community Edition)</a> 

#### Install the required dependencies on your local machine

1. **Ensure Python and pip are installed**:
   - Make sure Python and the Python package manager `pip` are installed on your system.
   - To check if `pip` is installed, run the following command in your terminal or command prompt:
     ```bash
     pip --version
     ```

2. **Run the pip command to install packages**:
   - <p>Open this project in your chosen IDE, ensuring the project is opened correctly. If the project is set up 
   properly, the `requirements.txt` file should be in the main project directory.</p>
   - <p>Open the IDE’s integrated terminal and use the following command to install all dependencies listed in the 
   `requirements.txt` file:</p>
   ```bash
   pip install -r requirements.txt
   ```

---

## Useful Resources
### General
- <a href="https://muted.io/note-frequencies/">Note Frequencies</a>
- <a href="https://www.michael-thomas.com/music/class/chords_notesinchords.htm">Notes in Chords (Major, Minor, 7th, Aug)</a>
- <a href="https://www.voxforge.org/home">VoxForge</a>
- <a href="https://draw.audio">Draw Audio</a>


### Lab. 01
- <a href="https://www.mixinglessons.com/bit-depth/">Bit Depth</a>
- <a href="https://www.youtube.com/watch?v=NYhkqXpFAlg">Working with Audio in Python (feat. Pedalboard) on YouTube.</a>


### Lab. 02
- <a href="https://youtu.be/spUNpyF58BY">But what is the Fourier Transform? A visual introduction. - 3Blue1Brown</a>
- <a href="https://youtu.be/bqGjh67x7IU">Understanding FFT in Audio Measurements - Audio Science Review</a>
- <a href="https://resources.pcb.cadence.com/blog/2020-time-domain-analysis-vs-frequency-domain-analysis-a-guide-and-comparison">Time Domain Analysis vs Frequency Domain Analysis: A Guide and Comparison</a>
- <a href="https://pressbooks.pub/sound/chapter/frequency-domain-graphs-2/#:~:text=Frequency%20domain%20graphs%20show%20much,strongly%20present%20in%20the%20sound.">FFTs and spectrograms</a>
- <a href="https://web.mit.edu/~gari/teaching/6.555/lectures/ch_DFT.pdf">Chapter 4 - THE DISCRETE FOURIER TRANSFORM</a>
- <a href="https://academo.org/demos/spectrum-analyzer/">Spectrum Analyzer</a>
- <a href="https://download.ni.com/evaluation/pxi/Understanding%20FFTs%20and%20Windowing.pdf">Understanding FFT's and Windowing</a>
- <a href="https://sensemore.io/what-is-cepstral-analysis/">Cepstral analysis</a>
- <a href="http://www.practicalcryptography.com/miscellaneous/machine-learning/tutorial-cepstrum-and-lpccs/">A Tutorial on Cepstrum and LPCCs</a>
- <a href="http://practicalcryptography.com/miscellaneous/machine-learning/guide-mel-frequency-cepstral-coefficients-mfccs/">Mel Frequency Cepstral Coefficient (MFCC) tutorial</a>


### Lab. 03
- <a href="http://hyperphysics.phy-astr.gsu.edu/hbase/Sound/beat.html#:~:text=When%20two%20sound%20waves%20of,%22beating%22%20or%20producing%20beats.">Beats Theory</a>
- <a href="https://www.youtube.com/watch?v=twppI9Eizp8">Sound Intensity Level in Decibels & Distance</a>
- <a href="https://www.youtube.com/watch?v=M-OMq4QsPfY">Beat Frequency Physics Problems</a>
- <a href="https://www.ansys.com/blog/what-is-auditory-masking">Auditory Masking</a>
- <a href="https://www.beis.de/Elektronik/Correlation/CorrelationCorrectAndWrong.html">False and Correct Audio Correlation Measurements</a>
- <a href="https://liquidinstruments.com/blog/cross-correlation-and-spectrum-analysis/#:~:text=Essentially%2C%20cross-correlation%20is%20the,a%20lagged%20version%20of%20itself.">Cross-Correlation</a>


## Lab. 04
- <a href="https://course.ece.cmu.edu/~ece792/handouts/RS_Chap_LPC.pdf">Linear Predictive Coding of Speech</a>
- <a href="https://speechprocessingbook.aalto.fi/index.html">Introduction to Speech Processing</a>
- <a href="https://phonicshero.com/voiced-vs-unvoiced-sounds-whats-the-difference/">Voiced and Unvoiced Sounds</a>
- <a href="https://en.wikipedia.org/wiki/Vocal_tract">Vocal Tract</a>
- <a href="https://en.wikipedia.org/wiki/Levinson_recursion">Levinson Recursion</a>


## Lab. 05
- <a href="https://en.wikipedia.org/wiki/Mel_scale">Mel Scale</a>
- <a href="https://en.wikipedia.org/wiki/Decorrelation">Decorellation</a>
- <a href="https://medium.com/@MuhyEddin/feature-extraction-is-one-of-the-most-important-steps-in-developing-any-machine-learning-or-deep-94cf33a5dd46">Mel-frequency cepstral coefficients (MFCCs)</a>


## Lab. 06
- <a href="https://www.youtube.com/watch?v=dD6_Bajj2DI&t=1s">The Magic Of Mid Side</a>


## Lab. 07
- <a href="https://youtu.be/eOSiH2MbRgg">Ecoplate II Plate Reverb Hardware Demo</a>
- <a href="https://youtu.be/5qEdMno9B_w">Anasounds Element Analog Spring Reverb</a>
- <a href="https://youtu.be/XsVF1rySAmU">Spring Reverb vs Plate Reverb: What's The Difference?</a>
- <a href="https://youtu.be/h3F-8kBAac8">Inside The Abbey Road Reverb Chamber</a>


## Credits
<ul> 
    <li>Thomas, J. (2009, January 1). Blues guitar loop 1 Accessible at <a href="https://youtu.be/ipnkP7j1yms?list=OLAK5uy_l6sZ_rLGmbIqCpERpdm1WqI2s1UeGN9QM">YouTube</a>.</li>
    <li>Thomas, J. (2009, January 1). Funk Guitar Electric 39 Accessible at <a href="https://youtu.be/rzkjGVySc0I?list=OLAK5uy_l6sZ_rLGmbIqCpERpdm1WqI2s1UeGN9QM">YouTube</a>.</li>
    <li>Thomas, J. (2009, January 1). Funk Guitar Electric 40 Accessible at <a href="https://youtu.be/VRgIBTVmRg8?list=OLAK5uy_l6sZ_rLGmbIqCpERpdm1WqI2s1UeGN9QM">YouTube</a>.</li>
    <li>Thomas, J. (2009, January 1). Funk Guitar Electric 41 Accessible at <a href="https://youtu.be/Cjh0Yy7xQLY?list=OLAK5uy_l6sZ_rLGmbIqCpERpdm1WqI2s1UeGN9QM">YouTube</a>.</li>
    <li>Song Thrush recording by Patrik Åberg, XC26981. Accessible at the <a href="http://www.xeno-canto.org/26981">Link</a>.</li>
    <li>Humpback whale recording by "The Voices of Glacier Bay Project". Accessible at the <a href="http://www.nps.gov/glba/naturescience/soundclips.htm">Link</a>.</li>
    <li>Police Siren recording by Vlammenos. Accessible at the <a href="http://soundbible.com/581-Police-Siren-3.html">Link</a>.</li>
</ul>
