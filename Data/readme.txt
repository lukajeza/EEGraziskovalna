1. Folder EEG_DE_features: contains DE features of 16 participants and a jupyter notebook file giving example code to load the data. Feature data are named in "subjectID_sessionID.npz". For example, file "1_123.npz" means that this is the DE features for the first subject and the DE features from three sessions are included.

2. Folder EEG_raw:  contains raw EEG data (.cnt file) collected with Neuroscan device and a jupyter notebook file giving example code to load the data. Raw data are named in "subjectID_sessionID_date.cnt" format. For example, "1_1_20180804.cnt" means that this is the raw data of the first subject and first session. **Notice: session number are given based on the stimuli materials watched, not based on the time.**

3. Folder Eye_movement_features: contians extracted eye movement features.

4. Folder Eye_raw: contains excel files extracted from the eye tracking device.

5. Folder src: contains two subfolders "DCCA-with-attention-mechanism" and "MultualInformationComparison" which are DCCA models and mutual infromation calculating code used in paper "W. Liu, J. -L. Qiu, W. -L. Zheng and B. -L. Lu, "Comparing Recognition Performance and Robustness of Multimodal Deep Learning Models for Multimodal Emotion Recognition," in IEEE Transactions on Cognitive and Developmental Systems, doi: 10.1109/TCDS.2021.3071170."

6. File trial_start_end_timestamp.txt: contains start and end time of stimuli movie clips.

7. File emotion_label_and_stimuli_order.xlsx: contains emotion labels and stimuli orders.

8. File Participants_info.xlsx: contains meta-information of subjects.

9. File Scores.xlsx: contains feedback scores of participants.
