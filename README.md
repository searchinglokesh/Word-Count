# Audio to Audacity Label File Converter(Collab Edition)

This is a Python script that takes an audio file as input and converts it into an Audacity label file. The label file contains timestamps for each sentence spoken in the audio file along with a serial number, count of total number of words spoken and count of total number of English words spoken in the sentence.

## Before you start

This is automation for the project we were given which deals with manually creating labels for audio files for the Speech dataset in audacity for feature extraction. So remember that this is just a automation for the process so we are not creating a software for commercially using this, also yes we are currently using assr of iit madras and

## Prerequisites

Before using this script, you will need the following:

* Google collab
* ASR( Currently Constructing one but currently using IIT-Madras ASR ) - [ASR](https://asr.iitm.ac.in/asr/v2/)

## Installation

1. Clone the google collab repository

   ```
   git clone https://github.com/your-username/audio-to-audacity-label-file-converter.git
   ```

2. Install the required packages in the Collab Environment

## Usage

Will work upon this in later versions
<!-- 
To use this script, run the following command:

```
python audio_to_label.py <input_audio_file> <output_label_file>
```

Here, `<input_audio_file>` is the path to the audio file you want to convert and `<output_label_file>` is the path where you want to save the label file.

For example:

```
python audio_to_label.py audio_file.wav label_file.txt
```
 -->
<!-- This will create a label file with the name `label_file.txt` in the current directory.
 -->
## Output

The output Audacity label file will contain the following information for each sentence spoken:

* Start time: The timestamp for the start of the sentence in seconds.
* End time: The timestamp for the end of the sentence in seconds.
* Serial number: A unique serial number for each sentence.
* Count of total number of words spoken in the sentence
* Count of total number of English words spoken in the sentence

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* [IITM ASR System](https://asr.iitm.ac.in/asr/v2/) - An open source Automatic Speech Recognition (ASR) system developed by the Indian Institute of Technology Madras.
* [NLTK](https://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
