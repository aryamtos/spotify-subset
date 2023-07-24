# Spotify Subset

The 'Subset Spotify' includes file names from the Spotify Dataset (Tanaka et al. (2022)) for classifying language variations in Brazilian Portuguese. The selection of file names resulted from applying a filter to the original dataset metadata, focusing on idiomatic expressions and names or acronyms of locations.

### Segmentation File

The information regarding the track (music, female voice, male voice, and silence) and duration were segmented using the inaSpeechSegmenter available at  ‣ . The file segmentation_files_type.csv presents the following information:

- filename - the name of the original file
- type: whether it contains music, female voice, male voice, or silence
- start_time: the starting point of the segment with music, female voice, male voice, or silence
- end_time: the endpoint of the segment with music, female voice, male voice, or silence
- local: the specific city
- state: the state abbreviation
- region: the Brazilian region
- info: whether the audio contains only the capital city or municipalities and the capital city.

### Original File

The original file "original_files_ogg_spotify_dataset" contains general information about the audio files.

- filename - the name of the original file
- duration - the audio duration
- genre - the gender of the speakers (male, female, or both)
- local - the location of the speakers
- state - the state abbreviation
- region - the Brazilian region
