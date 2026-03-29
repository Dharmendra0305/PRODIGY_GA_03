# Markov Chain Text Generator 📝

![Project Status](https://img.shields.io/badge/Status-Completed-success) 
![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

**Prodigy Infotech Internship - Task 03**

## 🚀 Overview
This project implements a statistical text generation algorithm using Markov Chains. Instead of relying on complex deep learning, this model predicts the probability of the next word based on the current state (an $n$-gram of previous words). It serves as a lightweight, highly interpretable demonstration of natural language modelling.

*- Here’s the main interface of the Markov Chain Text Generator:*

![img](https://github.com/Dharmendra0305/PRODIGY_GA_03/blob/788f55ab281cea21727f88493967d91380bc1ec9/1.png)

## ✨ Features
* **Order-2 Markov Chain:** Uses word pairs for coherent text generation.
* **Custom Corpus Training:** Dynamically builds a probability dictionary from any provided text file.
* **Interactive Web UI:** Features a user-friendly Gradio interface for real-time text generation.
* **Cloud-Ready:** Fully optimised for seamless execution in Google Colab.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** `random`, `gradio`
* **Environment:** Google Colab / Jupyter Notebook

## ⚙️ Installation & Usage

### Running in Google Colab (Recommended)
1. Upload the `markov_generator.ipynb` notebook to Google Colab.
2. Upload your desired training text file (e.g., `dataset.txt`).
3. Run all cells. The Gradio UI public link will be generated at the bottom.

### Running Locally
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Dharmendra0305/PRODIGY_GA_03.git](https://github.com/Dharmendra0305/PRODIGY_GA_03.git)

2. **Install the required UI library:**
   ```bash
   pip install gradio

3. **Run the script:**
   (Ensure you save the Python code provided previously into a file named app.py)
   ```bash
   python main.py

4. **Access the Web UI:**
   - The terminal will output a local URL (e.g., http://127.0.0.1:7860).
   - If share=True is enabled in the code, a public gradio.live link will also be generated.

*- Example:*

![img](https://github.com/Dharmendra0305/PRODIGY_GA_03/blob/788f55ab281cea21727f88493967d91380bc1ec9/2.png)

## 🤝 Contribution Guidelines
Contributions are welcome! If you'd like to improve the code or add features:
1. Fork the repository.
2. Create a new branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a Pull Request.

## 📄 License
Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
