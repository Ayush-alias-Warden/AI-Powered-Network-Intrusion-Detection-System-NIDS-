# AI-Powered Network Intrusion Detection System (NIDS)

## 📌 Project Overview
This project is a real-time Network Intrusion Detection System (NIDS) built using **Python** and **Streamlit**. It leverages a **Random Forest Classifier** to analyze network traffic patterns and detect potential cyberattacks.

The system classifies network activity into two categories:
* **Benign:** Safe, normal traffic.
* **Malicious:** Potential threats (e.g., DDoS attacks, Port Scans).

## 🚀 Features
* **Machine Learning Model:** Uses Random Forest (Scikit-Learn) for high-accuracy classification.
* **Real-Time Dashboard:** Interactive UI built with Streamlit.
* **Traffic Simulator:** Built-in tool to generate synthetic network packets for testing.
* **Visual Analytics:** Displays confusion matrices and performance metrics.

## 🛠️ Installation & Setup
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/AI_NIDS_Project.git](https://github.com/YOUR-USERNAME/AI_NIDS_Project.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy scikit-learn streamlit seaborn matplotlib
    ```
3.  **Run the application:**
    ```bash
    python -m streamlit run nids_main.py
    ```

## 📸 Usage
1.  **Train the Model:** Click the "Train Model" button in the sidebar to initialize the AI.
2.  **Simulate Traffic:** Use the "Live Traffic Simulator" to input packet details (Flow Duration, Packet Count).
3.  **Analyze:** The system will flag the traffic as **Safe** (Green) or **Malicious** (Red).