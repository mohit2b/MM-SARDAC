We run all our experiments in NVIDIA A100-SXM GPU provided by Google Colab 

For obtaining the data for the model please follow the steps

Text data - It is available at https://github.com/soujanyaporia/MUStARD in data/sarcasm_data.json location. We also provide train, valid and test dialog ids with them.

Audio data - We first obtain raw video from https://github.com/soujanyaporia/MUStARD and convert those videos to audio format corresponding to the last utterance   of every dialog. The we proceed to obtain audio features in the same manner as described in https://github.com/thuiar/MIntRec/tree/main/tools/audio_preprocess.py

Video data - We get raws videos from https://github.com/soujanyaporia/MUStARD and obtain the video features corresponding to last utterance from https://github.com/soujanyaporia/MUStARD under Run the code section point 3 Download the pre-extracted visual features.

For running the model first run the sarcasm_only.ipynb and intent_only.ipynb files.

Then enter the saved weights into multitask_sarcasm.ipynb and multitask_intent.ipynb files.

Then proceed to run multitask_sarcasm.ipynb and multitask_intent.ipynb files to get the result.



