 **📊 EDA Analyzer App - LLM Powered**
 
  Welcome to the EDA Analyzer App, a powerful automated tool that performs Exploratory Data Analysis (EDA) using Python, Gradio UI, and LLM (Large Language Model) capabilities. 
  Simply upload your CSV dataset, and the app will generate summaries, missing value stats, visualizations, and even AI-driven insights.

 **🚀Features**
 
📁 Upload any CSV dataset.

📈 Auto-generates statistical summary using pandas.

🧼 Handles missing values (median/mode imputation).

📊 Visualizes distributions of numerical features and correlation heatmap.

🤖 AI-generated insights from dataset summary using Ollama LLM (e.g., Mistral).

🌐 Intuitive web interface built with Gradio.

**Technologies Used**

Python 3.x

Gradio – For creating the interactive web app

Pandas – Data manipulation

Seaborn & Matplotlib – Visualizations

Ollama – For AI-powered dataset analysis using LLMs like Mistral

**📦 Installation**

# Clone the repo
git clone https://github.com/nwngrg/eda-analyzer-app.git
cd eda-analyzer-app

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

**📂 Project Structure**

.
├── app.py                             # Main Gradio App with all EDA logic
├── code.ipynb                         # Jupyter notebook version (exploratory or prototyping)
├── requirements.txt                   # List of dependencies (optional to create)
├── README.md                          # You're here!
├── data/                              # Data files for analysis
│   ├── data.csv
│   └── LT_Construction_Project_Timelines_No_Null.csv
└── plots/                             # Visualizations / Distribution Plots
    ├── Actual Cost (INR)_distribution.png
    ├── Budget (INR)_distribution.png
    ├── Number of Workers_distribution.png
    ├── Planned Duration (days)_distribution.png
    ├── Safety Incidents_distribution.png
    └── Schedule Variance (days)_distribution.png

**🧠 AI Insights**

The app uses Ollama’s mistral model to provide contextual insights based on the dataset summary. This helps in better understanding trends, anomalies, and key patterns.,

**📸 Sample Output**

Summary statistics

Missing value report

Distribution plots

Correlation heatmap

Natural language insights

**🔒 Note**

Ensure ollama is installed and configured properly.

Make sure the LLM model (e.g., mistral) is downloaded and available via ollama.

**🙌 Acknowledgments**

Ollama for making LLMs locally accessible

Gradio for beautiful UIs with minimal code

Seaborn for elegant visualizations

 Contact
Author: Naveen Garg
📧 nwngrg@gmail.com
🌐 LinkedIn https://www.linkedin.com/in/naveen-garg-27335a320/ GitHub link:-  https://github.com/nvngrg 




