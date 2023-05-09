# Audio to Audacity Label File Converter(Collab Edition)

This is a Python script that takes an audio file as input and converts it into an Audacity label file. The label file contains timestamps for each sentence spoken in the audio file along with a serial number, count of total number of words spoken and count of total number of English words spoken in the sentence.

## Before you start

This is automation for the project we were given which deals with manually creating labels for audio files for the Speech dataset in audacity for feature extraction. So remember that this is just a automation for the process so we are not creating a software for commercially using this, also yes we are currently using asr of iit madras and doing this and 

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

Collab Version:
Open [IIT MADRAS ASR](https://asr.iitm.ac.in/asr/v2/)
![image](https://user-images.githubusercontent.com/76202394/237011659-7129282a-1469-4c55-84ae-2869b8b66181.png)
Upload the audio file here and select English for the detection of english words from the audio.
![image](https://user-images.githubusercontent.com/76202394/237016190-d499e142-6317-4302-9b0a-8afdb869438f.png)
Then save the transcription in the inputtxt in collab.
Do the same for the hindi
Then select Hindi for detction of the entire words in the audio since the hindi asr detects the english sentences as audio.
Then insert it into the Hinditxt part.
Then run the cell voila you have your labels data now save this into a txt fil now you can directly import it into audacity for labels and further use it gfor feature extraction for feature extraction.

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
