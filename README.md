# wav_splitter


# Function

The purpose of this program is to split an arbitiary long wav file into segments. The main application was used to create audio datasets.

example of how to format command.
'''
python wav_splitter.py -sf ____ -sd __________ [Optional Arguements]
'''

'''
usage: wav_split.py [-h] -sf SOUND_FILE [-sd SAVE_DIR] [-ss SAMPLE_SIZE] [-cv CSV_SAVE] [-head HEAD]
                    [-class CLASS_ID] [-name DATASET_NAME]

optional arguments:
  -h, --help            show this help message and exit
  
  -sf SOUND_FILE, --sound_file SOUND_FILE
                        path to soundfile
                        
  -sd SAVE_DIR, --save_dir SAVE_DIR
                        path to save dir
                        
  -ss SAMPLE_SIZE, --sample_size SAMPLE_SIZE
                        the size of each sample
                        
  -cv CSV_SAVE, --csv_save CSV_SAVE
                        True if metadata
                        
  -head HEAD, --head HEAD
                        header to wav files
                        
  -class CLASS_ID, --class_id CLASS_ID
                        classID -- will default to 1
                        
  -name DATASET_NAME, --dataset_name DATASET_NAME
                        name of the dataset

'''


