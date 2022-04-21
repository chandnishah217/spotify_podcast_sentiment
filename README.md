# W266-NLP-final-project
Repository for team project for MIDs W266 NLP Class

[Final report can be found here](https://github.com/chandnishah217/spotify_podcast_sentiment/blob/main/Emotion_Detection_Spotify_W266.pdf)

[Presentation slides can be found here](https://github.com/chandnishah217/spotify_podcast_sentiment/blob/main/Emotion%20Analysis%20on%20Podcast%20Corpus-%20presenation.pdf)

# Directory structure

## data/
### raw/
Repository for the raw podcast data from spotify, not synced to github

### intirim/
Repository for the pre-processed version of the spotify, also not synced due to size

### Files used for manual tagging
- podcast_sentences_5000.csv
- podcast_sentences.csv
- tagging_context_only_5k.csv
- rejoined_selected_podcast_5000_sentences.csv
- rejoined_selected_podcast_5000_sentences_untagged_context_only.csv

### training sets with manual tags

Initial version:
- test.csv
- training.csv
- val.csv

Correctly Stratified:
- strat_test.csv
- strat_training.csv
- strat_val.csv

### Files used for MLM training
- podcast_sentences_high_conf_20000_with_context.csv
- podcast_sentences_high_conf_2000_with_context_test.csv
- podcast_sentences_high_conf_2000_with_context_validation.csv
- podcast_sentences_high_conf_500000_with_context_test.csv

### Synthetic tags files
- 100K_results_model_generated.csv
- podcast_sentences_high_conf_100K_for_PLM.csv

### output predictions for best model
- ge_mlm_val_preds.csv


## notebooks/

### covidworry/
Directory for notebooks on a related data set, not used for project

### goemotion/
Directory for notebooks for zero shot GoEmotion execution, and fine tuning on our data set

### Bert_spotify*
Notebooks for training our data ontop of various models

### Pretraining/
Directory for notebooks for doing the MLM pretraining

### Synthetic_tagging/
Directory for notebooks for doing sythetic tagging

### tag-data/
Directory for processing raw data and interfacing with tagging system.  Also includes notebooks for tag data exploration.

## Figures
A repository for figures used in the paper

