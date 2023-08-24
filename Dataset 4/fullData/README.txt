EEG during mental arithmetic task

Igor Zyma, Sergii Tukaev, Ivan Seleznov

The data files with EEG are provided in EDF (European Data Format) format. Each folder contains two recording files per subject: 
with “_1” postfix -- the recording of the background EEG of a subject (before mental arithmetic task)
 with “_2” postfix -- the recording of EEG during the mental arithmetic task. 

In this experiment all subjects are divided into two groups: 
Group “G” (24 subjects) performing good quality count (Mean number of operations per 4 minutes = 21, SD = 7.4 ), 
Group ”B” (12 subjects) performing bad quality count (Mean number of operations per 4 minutes = 7, SD = 3.6).  
In the file “subjects_info.xlsx” the “Count quality” column provides info which subjects correspond to which group (0 - Group ”B”, 1 - Group “G”). Additionally, file “subjects_info.xlsx” provides basic information about each subject (gender, age, job, date of recording).

Both EDF and EDF+ formats are free and can be viewed using free software such as:
Polyman (for MS-Windows only; for details, please follow the link)
EDFbrowser (for Linux, Mac OS X, and MS-Windows; at www.teuniz.net)
LightWAVE and the PhysioBank ATM, platform-independent web applications from PhysioNet
WAVE and other applications for Linux, Mac OS X, and MS-Windows in the WFDB Software Package, also from PhysioNet

For using the following EDF files in Python code, we suggest using the PyEDFlib for  processing the files (https://github.com/holgern/pyedflib/tree/master/pyedflib). 

The EEGs were recorded monopolarly using Neurocom EEG 23-channel system  (Ukraine, XAI-MEDICA). The silver/silver chloride electrodes were placed on the scalp according to the International 10/20 scheme. All electrodes were referenced to the interconnected ear reference electrodes. A high-pass filter with a 30 Hz cut-off frequency and a power line notch filter (50 Hz) were used. All recordings are artifact-free EEG segments of 60 seconds duration. At the stage of data preprocessing, the Independent Component Analysis (ICA) was used to eliminate the artifacts (eyes, muscle, and cardiac overlapping of the cardiac pulsation). Arithmetic task was the serial subtraction of two numbers. Each trial started with the communication orally 4-digit (minuend) and 2-digit (subtrahend) numbers (e.g. 3141 and 42)

The participants were eligible to enroll in the study if they had normal or corrected-to-normal visual acuity, normal color vision, had no clinical manifestations of mental or cognitive impairment, verbal or non-verbal learning disabilities. Exclusion criteria were the use of psychoactive medication, drug or alcohol addiction and psychiatric or neurological complaints.

