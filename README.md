
# 🗣️ Homophone Frequency Analyzer

This project provides a simple Python script to **analyze and visualize the frequency of homophones** in a list of speech-to-text transcriptions. It uses a predefined dictionary of homophones and leverages `matplotlib` for visualization.

## 📌 Features

- Parses a list of transcriptions.
- Identifies and counts homophones using a customizable dictionary.
- Visualizes the frequency of each homophone group using a bar chart.

## 🔍 Example

Here’s a sample output from the script:

<img src="homophone_plot_example.png" alt="Homophone Frequency Plot" width="600">

## 🧠 How It Works

1. A dictionary of homophone groups is defined, e.g., `"to": ["to", "too", "two"]`.
2. Each transcription is processed word by word.
3. Words that match any in the homophone dictionary are counted.
4. The total frequency of each homophone group is plotted as a bar chart.

## 📂 Project Structure

```
.
├── homophone_analyzer.py       # Python script with homophone frequency logic and plot
├── README.md                   # Project overview and instructions
└── requirements.txt            # Required Python libraries
```

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3 installed.

Install required libraries:

```bash
pip install matplotlib
```

### Running the Script

Run the Python file:

```bash
python homophone_analyzer.py
```

This will open a window showing the bar chart of homophone frequencies found in the sample transcriptions.

## 🛠️ Customization

- Add more homophones to the `homophones_dict` to suit your analysis.
- Replace the `predicted_transcriptions` list with your own data from speech-to-text output.

## 📃 License

This project is licensed under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/homophone-analyzer/issues) or submit a pull request.
