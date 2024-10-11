# Currently work in progress

- This is a pipeline i am building to finetune Meta's pretrained model Musicgen on various types of music. I previously had trained it using the small model and 120 instrumentals amounting to about 5.5 hours of music.

- There are 2 options for the scraper one using yt-dl combined with your google api this is more customisable and allows for more downloads and can be found in the audio_download.ipynb file, the second is the built in scraper in the actual finetuning notebook which limits you to youtube playlists.
  
-  They are downloaded in WAV format and are split into 30 sec chunks to be passed into the model.

Note: The updates to this model would be the ability to generate longer sequences of music as well as an integrated diffusion model to refine the sample rate and audio quality

Resources used: Google collab T4 GPU, and a taste for music

