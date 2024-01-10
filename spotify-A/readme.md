<h2>Spotify A subset</h2>

<h3>Segmentation File</h3>

The information regarding the track (music, female voice, male voice, and silence) and duration were segmented using the inaSpeechSegmenter available at (https://github.com/ina-foss/inaSpeechSegmenter) . The file 'segmentation_files_spotifyA.csv' presents the following information:

- filename - the name of the original file
- type: whether it contains music, female voice, male voice, or silence
- start_time: the starting point of the segment with music, female voice, male voice, or silence
- end_time: the endpoint of the segment with music, female voice, male voice, or silence
- local: the specific city
- state: the state abbreviation
- region: the Brazilian region
- info: whether the audio contains only the capital city or municipalities and the capital city.

<h3>Identifiers</h3> 

The file "ids_spotifyA.csv" contains general information about the audio files.

- filename - the name of the original file
- duration - the audio duration
- genre - the gender of the speakers (male, female, or both)
- local - the location of the speakers
- state - the state abbreviation
- region - the Brazilian region
