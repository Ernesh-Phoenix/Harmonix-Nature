# AI Nature Sound Generator 🌿

**Generate custom nature-inspired sounds on demand!** This Streamlit app uses AI-driven audio processing techniques to fetch, process, and enhance nature sound clips based on your input. Transform simple prompts like “rainforest” or “ocean waves” into immersive, high-quality audio experiences.

## 🚀 Features

- **Intuitive UI** – Enter a prompt to instantly start creating!
- **Audio Effects** – Control volume, echo, and apply low-pass filters.
- **Customizable Settings** – Fine-tune parameters like echo decay and volume.
- **Output as WAV** – Download generated soundscapes to enjoy or share.

## 💻 How it Works

1. **User Input** – Enter a nature sound prompt and adjust settings.
2. **Fetch Audio** – App connects to Freesound API, downloading relevant sounds.
3. **Process Sound** – Normalize audio, apply noise reduction, add echo, control volume, and apply a low-pass filter.
4. **Combine and Output** – Blends processed clips and saves them as `.wav`.

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-nature-sound-generator.git
   
2. Install Dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the App:
   ```bash
   streamlit run app.py

## 🛠️ Usage

1. **Prompt** – Enter your desired nature sound (e.g., "birds chirping," "ocean").
2. **Volume** – Adjusts the audio volume.
3. **Echo Decay** – Controls the intensity of the echo effect.
4. **Low-Pass Filter** – Limits high frequencies for a softer sound.

## 🤖 Technologies Used

1. **Streamlit** – Interactive web UI
2. **Librosa** – Audio processing library
3. **Freesound API** – Access to nature sound datasets
4. **NumPy & SciPy** – Signal processing

## 📝 License

This project is licensed under the **MIT License**.
