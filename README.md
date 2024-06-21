# Text-To-Speech-TTS-Synthesis.

Code Explanation:
--> This MATLAB code demonstrates a basic example of text-to-speech (TTS) synthesis.
--> The goal is to convert the input text (“Hello, how are you today?”) into a synthesized speech signal.
--> Here’s how the code works:
      ~ It initializes an empty speech signal y.
      ~ For each character in the input text:
          * If the character is a space, it inserts silence (100 ms duration).
          * Otherwise, it inserts a random noise segment (for demonstration purposes).
      ~ The resulting speech signal is normalized to the range [-1, 1].
      ~ Finally, the synthesized speech is played using the sound function.
