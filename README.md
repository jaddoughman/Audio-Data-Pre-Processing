# Audio-Data-Pre-Processing

## Part 1: Data Mining
You are given a soundscloud_urls.csv file containing URLs to SoundCloud.com. You are tasked with extracting the audio files, the name of the author and the track name from the provided links, save this data in a `.csv` and display the dataframe in your notebook. All audio file must be saved as `.wav` in the `./data` directory. 

## Part 2: Data Processing and Visualization
Once you have downloaded your audio files, you are tasked with pre-processing your data by converting the raw waveform to a spectrogram using the Fast Fourier Transform (FFT). You can find more information about the FFT [HERE](http://www.dspguide.com/ch12.htm)
Finally, your must convert your spectrogram from Hz range to the mel-scale. More information about me-scaling can be found [HERE](http://pdf-s3.xuebalib.com:1262/249gn34RBxh1.pdf)

**Note:** You are not permitted to use built-in functions to perform FFT and mel-scale operations mentioned in part 2. 
