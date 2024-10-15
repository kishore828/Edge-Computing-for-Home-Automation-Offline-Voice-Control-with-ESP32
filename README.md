# Edge-Computing-for-Home-Automation-Offline-Voice-Control-with-ESP32
dumping a speech recognisation model in esp32 using Arduino


To deploy a model on the ESP32, follow these key steps:

1️⃣ **Train the Model**: First, you need to train your model. You can do this using TensorFlow, and once trained, convert it into a **TensorFlow Lite** model.

2️⃣ **Convert to C Code**: After conversion, turn the model into **C code** and declare it as a library function 📚. This allows you to call the model directly in your Arduino code! 🎯

3️⃣ **Edge Impulse Option**: Alternatively, use **Edge Impulse** to streamline the process. Simply upload your dataset 📊, and it will automatically train the model and provide a ready-to-use file 🚀.

4️⃣ **Arduino Setup**: Ensure your Arduino **IDE uses IDF version 5 or below** ⚙️. This is crucial for TinyML model support 🧠. 

5️⃣ **Model Execution**: For specific commands, you can implement **automation** or utilize **speech-to-text** 🗣️. This converts audio directly into text, completing the process! 🎤➡️📄

