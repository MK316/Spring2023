# Experiment 01: Assessing L2 accentedness

Here is a step-by-step guide to prepare a perception experiment using the ExperimentMFC object in Praat, where participants will rate 18 sentence stimuli on a scale of 1 (Heavily accented) to 6 (Native like):

1. Create stimuli files: Record or obtain the 18 sentence stimuli as individual audio files (preferably in WAV format). Name them systematically, e.g., stimulus1.wav, stimulus2.wav, etc.

2. Organize stimuli: Create a folder named "stimuli" and place all the audio files within it. This folder will be used to store and organize the stimuli for the experiment.

3. Create response categories: Create a text file named "response_categories.txt" with the following content, defining the scale from 1 to 6:
4. Create a stimulus table: Create a text file named "stimulus_table.txt" with the following format, listing the file names of the 18 stimuli and their corresponding categories: The "0" here indicates that there is no correct response, as this is a subjective rating task.
5. Create a Praat script: Create a new Praat script with the following code, adjusting the parameters as needed: Replace /path/to/your/stimuli/folder/ with the actual path to the folder containing your stimuli and other files.
6. Run the experiment: Open Praat, go to "Praat > Open Praat script", and select the script you created in step 5. Press "Run" to execute the script and start the experiment.
7. Collect data: Participants will listen to the sentences, rate them on the scale of 1 to 6, and their responses will be saved in the "results.txt" file.
8. Analyze and interpret the data: Once all participants have completed the experiment, analyze the data in the "results.txt" file using statistical methods to answer your research questions and draw conclusions about accent perception.
