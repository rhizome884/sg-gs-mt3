# sg-gs-mt3
SampleGuitar-GuitarSet-MT3: A partition of the SampleGuitar2026 dataset that features GuitarSet symbolic data with MIDI velocity estimates generated using a velocity sensitive CRNN guitar transcription model. MT3 refers to the GuitarSet dataset split, in which the 1st and 2nd chord progressions are used as the train split, and the 3rd progression is used as the test split.

## Notes
- The dataset does not contain the 2 annotations with timing errors. I had corrected these annotations, but I'd need to process them with the CRNN to produce velocity estimates, and I don't have time for the sake of 4 short midi files.
- The CP1 mix and mic and CP2 mix and mic MIDI differs in length. This overall length appears to be more or less the same and the solo and comp files all appear to be aligned. The CP3 MIDI files are approx identical in length. This should not be an issue as CP1 and CP2 files are restricted to the train set, so cross contamination between these two CPs can be permitted. 



