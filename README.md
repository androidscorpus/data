# data
Androids Depression Corpus

A full description of the Androids Corpus can be found in the following paper:

<a href="https://www.dropbox.com/s/zojvx4guqu1dau9/Androids-Corpus-Interspeech-2023.pdf?dl=0">Fuxiang Tao, Anna Esposito and Alessandro Vinciarelli, "The Androids Corpus: A New Publicly Available Benchmark for Speech Based Depression Detection", Proceedings of Interspeech, 2023</a>

The data can be downloaded at the following link (3.69 Giga Bytes): <a href="https://www.dropbox.com/s/qi7a3bd7wo6kwim/Androids-Corpus.zip?dl=0">Androids Corpus</a>

By downloading the data, you accept the following Terms and Conditions:

- The data must be used for academic research (non-commercial) purposes only;
- The Corpus must not be further distributed;
- The Corpus cannot be broadcast and/or made publicly available anywehere else than here.

If you have any questions, please contact the paper's authors:

- Fuxiang Tao: <a href="mailto:Fuxiang.Tao@glasgow.ac.uk">Fuxiang.Tao@glasgow.ac.uk</a>
- Anna Esposito: <a href="mailto:Anna.Esposito@unicampania.it">Anna.Esposito@unicampania.it</a>
- Alessandro Vinciarelli: <a href="mailto:Alessandro.Vinciarelli@glasgow.ac.uk">Alessandro.Vinciarelli@glasgow.ac.uk</a>




<hr>

The Corpus includes the following material:

- Directory "Reading-Task": 112 audio files, 54 in the subdirectory "HC" (Healthy Controls) and 58 in the subdirectory "PT" (Patients);
- Directory "Interview-Task/audio": 116 audio files, 52 in the subdirectory "HC" and 64 in the subdirectory "PT";
- Directory "Interview-Task/audio_clip": 874 audio files distributed over 116 subdirectories, each corresponding to one of the 116 speakers that participated in the Interview Task;
- fold-list.csv: lists of the files to be included in each of the 5 folds used for the development of the baseline approaches;
- Androids.conf: OpenSMILE config file used for the extraction of the features from the audio files;
- interview_timedata.csv: segmentation into turns of the audio data in subdirectory Interview-Task/audio;

The audio files in the directory "Reading-Task" are the recordings of the participants that read the fairy tale "The Wind of the North and the Sun" by Aesop.

The audio files in the directory Interview-Task are the recordings of the participants that were involved in an interview. 

The naming convention of the auduo files is as follows:

nn_XGmm_t.wav

where nn is a unique integer identifier such that, in a given group, files with the same nn contain the voice of the same speaker (there is a trailing 0 for numbers lower than 10), X is an alphabetic character corresponding to the speaker’s condition (P for depression patient and C for control), G is an alphabetic character that stands for the speaker’s gender (M for male and F for female), mm is a two-digits integer number corresponding to the speaker’s age, and t is an integer number between 1 and 4 accounting for the education level (1 corresponds to primary school and 4 corresponds to university). The letter X was used for the 2 participants who did not provide information about this aspect. There is no indication of the task because recordings corresponding to RT and IT are stored in different directories.

Please note that the identifier nn is unique within a group, meaning that the same identifier (e.g., 27) can be found in both depression and control groups. However, only one member of the group depression and only one member of the group control have the same identifier.

In this respect, every participant can be uniquely identified through the string nn_X, where X is the character accounting for the condition (see above).

<hr> 
