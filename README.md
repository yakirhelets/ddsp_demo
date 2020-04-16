# ddsp_demo
A demonstration of trained DDSP model. It is highly recommended to *open DDSPDemo.ipynb with* ***Google Colab***.

1. Repository structure: of the code in the src/ folder: What is implemented in each package/module.
   - **DDSPDemo.ipynb**: The file from which the demo is run.
   - **sources/audio_examples**: Directory contains some audio samples that can be resynthesized in the notebook (included only in the repsitory).
   - **sources/models**: Directory contains the models produced during the experiments (included only in the repsitory).
   - **sources/resynthesis**: Directory contains the results produced by the model different models  (included only in the repsitory):
     - double bass original.wav is one the original audio smaples.
     - double bass resynthesis <number_of_steps>.wav files are the reconstructions of the double bass model, with respect to the number of steps of the model.
     - dbass_\<number of steps>_resysnthesis_singing.wav are the resynthesized audio files from "somewhere over the rainbow" singing audio example, with respect to the number of steps of the model.
2. Steps to reproduce:
   - Open the DDSPDemo.ipynb notebook and open it in Google Colab by using "Open in Colab" badge. 
   - Make sure to use a GPU runtime, click: Runtime -> Change Runtime Type -> GPU
   - Press the ▶️ button on the left of each of the cells
