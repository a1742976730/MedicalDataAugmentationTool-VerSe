The CV is set up such that scans from the same patient are in the same training or validation set and that the landmark distributions are approximately the same for every set. (see `landmark_distributions.pdf`)
The landmark files are generated with the script `../other/preprocess_landmarks.py` and setting `verse2020 = True`. The landmark file generated from this script is under `landmarks.csv`. If you decide to run the script yourself, due to some naming inconsistencies, you also need to rename the file `GL124_CT_ax-iso-ctd.json` to `GL124_CT-ax-iso-ctd.json` as well as `GL240_CT_ax-iso-ctd.json` to `GL240_CT-ax-iso-ctd.json`.