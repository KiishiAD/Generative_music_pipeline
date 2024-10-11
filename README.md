# Currently work in progress

- This is a pipeline i am building to finetune Meta's pretrained model Musicgen on various types of music. It uses the small model and 120 instrumentals amounting to about 5.5 hours of music.

- These songs are downloaded from youtube using the audio download script you can find in the audio_download ipynb file(The songs downloaded for this repo were from the breakcore genre).
-  They are downloaded in WAV format and are split into 30 sec chunks to be passed into the model.

Note: The code at the moment is a bit messy but future updates would include a complete guide, and a tutorial with notes on the notebook.

Resources used: Google collab T4 GPU, and a taste for music

