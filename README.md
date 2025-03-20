📟 Morse Code Encoder/Decoder
🛠️ Project Overview
This Arduino sketch lets you encode and decode Morse Code!

🔹 Decode by keying in Morse sequences with a button.
🔹 Encode by typing letters into the Serial Monitor.
🔹 Watch the LED flash and listen to the buzzer beep as the code is processed.

This project is inspired by the book "Programming Arduino" by Simon Monk (©2016), with some code lines adapted from there.

🔧 Components Needed

🔹 Arduino board
🔹 Piezo buzzer or speaker (connected to pin 2 & ground)
🔹 Button (connected between pin 8 & ground)
🔹 LED (positive leg to pin 13, negative leg with 220Ω resistor to ground)


💡 Features

✅ Encode letters and numbers to Morse Code.
✅ Decode Morse Code sequences using a button.
✅ Plays a sound and flashes an LED during transmission.
✅ Unrecognized sequences give a warning beep and show ?.
✅ Includes a demo that flashes JONOK in Morse Code at startup.


⚡ Usage Instructions
1️⃣ Upload the sketch to your Arduino board.
2️⃣ Open the Serial Monitor (9600 baud).
3️⃣ To Encode:

Type a word or number, press Enter, and watch it convert to Morse Code.

4️⃣ To Decode:

Press the button for short taps (.) and long taps (-).
The LED and buzzer will activate.
A short pause signals a new letter, and a longer pause signals a new word.

5️⃣ Practice:

Type a word in the Serial Monitor.
Listen and try to replicate the sound with button presses.

🚀 Tip: Adjust the Morse speed with dotLength (default = 240 ms, ~5 WPM).

🔥 Demo Output
On startup, the LED blinks and the buzzer sounds JONOK in Morse Code:
J .---  
O ---  
N -.  
O ---  
K -.-


🧠 Future Improvements

🔹 Add support for punctuation.
🔹 Implement adjustable speed via Serial input.
🔹 Save decoded messages for later.


🔖 Credits

✨ Code by Oompah (March 3, 2023)
📘 Inspired by "Programming Arduino" by Simon Monk

Happy coding! 🔧✨
