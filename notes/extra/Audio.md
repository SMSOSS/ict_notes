# All about Sounds #

- Sound wave
    - bunch of wave frequencies
    - 高音 = high frequency
    - 低音 = low frequency
    - The more closely packed, the higher the frequency
    - 高低 in graph affect 大細聲
 - How to turn sound wave into 0 and 1?
    - Give it a line in middle and label it as 0
    - Divide it into different levels
    - Take reading of every milisecond
    - only register time and wave position 

- What about stuff between milliseconds?
    - we use sampling rate 👌
    - Normal MP3 sampling rate = 44100Hz 
    - Common music = 16bit
    - Bit resolution 
        - 8bit = 2⁸
          - Define a soundwave into 256 levels
           - 16bit = 2¹⁶
    - Do 44100 samples every second, and by 256 levels for the soundtrack.

- MP3 usually compressed by 1/4 or 1/5 

- How to calculate?
Sample rate × Bit rate × audio length × compression ratio

- Audio file formats
    - WAV
         - Uncompressed
    - MP3
         - compressed
    - AAC
        - Apple format
     - WMA
         - Windows format
     - Midi
          - instrument + note + time
          - it is typed not recorded
          - smallest in size :)
