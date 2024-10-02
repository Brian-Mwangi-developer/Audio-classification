# Capuchin Bird Call Detection

This project focuses on processing and analyzing audio data to identify the presence of Capuchin birds and distinguish them from other sounds in the forest. By sorting the audio into Capuchin bird calls and non-Capuchin bird audio, we can determine the density of Capuchin bird calls in different audio samples. The final result identifies which audio contains the highest number of Capuchin bird calls and exports this analysis as a CSV file.

## Objectives
Sort Audio: Classify provided audio files into two categories:

- Capuchin bird calls.
- Non-Capuchin bird audio.
- Analyze Call Density: Using the provided forest audio data, identify which audio samples contain the highest density of Capuchin bird calls.

Export Results: Export the analysis results, including the audio file names and Capuchin call densities, into a CSV file.

Steps Overview
### Preprocess Audio:

Load the audio files and convert them into a consistent format (mono, 16 kHz).
Use spectrograms to visually represent the audio for machine learning analysis.

### Train Model:

Train a machine learning model to classify the audio files as either containing Capuchin bird calls or non-Capuchin bird audio.

### Detect Call Density:

Process the forest audio files and calculate the density of Capuchin bird calls (i.e., how many instances of the bird's call are detected in each file).

### Export Results:

Save the results in a CSV file, including the audio file names and their corresponding Capuchin bird call density.
Output
The final output will be a CSV file containing:

- The names of the forest audio files.
- The detected Capuchin bird call density for each file.