📡 Real-time Network Traffic Analysis Dashboard with Python & Streamlit
🛠️ Built by: [Tom]
🔍 Inspired by Chaitanya Rahalkar’s tutorial on freeCodeCamp

📝 Project Overview
This project is a real-time dashboard that captures and visualizes network traffic using Python. It uses Streamlit for the web interface, Scapy for packet sniffing, and Plotly for interactive graphs. You can monitor incoming/outgoing packets, view protocol distributions, and inspect the top IP sources in your network — all updated live.

This was built as a hands-on way to understand networking, real-time data processing, and building dashboards.

⚙️ Key Features
📡 Live capture of packets (TCP, UDP, ICMP)

📊 Real-time interactive charts using Plotly

🕒 Auto-updating dashboard every 2 seconds

🧾 Table of recently captured packets

💡 Modular code structure with threading

🧰 Tools & Libraries
Python 3.8+

Streamlit – for building the dashboard UI

Scapy – for capturing packets

Pandas – for data wrangling

Plotly – for graphs and charts

📁 Folder Structure
bash
Copy
Edit
network-dashboard/
├── dashboard.py         # Main app script
├── README.md            # Project documentation

🔧 Installation

git clone https://github.com/your-username/network-dashboard.git
cd network-dashboard
pip install streamlit scapy pandas plotly
▶️ How to Run
Admin privileges required for packet sniffing

Linux/macOS:
sudo streamlit run dashboard.py
Windows:
Open terminal as administrator:


streamlit run dashboard.py


🌱 Future Ideas
🌍 Add GeoIP mapping for IP visualization

📦 Analyze packet payloads

🧠 Integrate ML models for anomaly detection

🚨 Custom alerts for suspicious traffic


📚 Credits
Inspired by: Chaitanya Rahalkar’s article on freeCodeCamp

Thanks to the developers of Streamlit, Scapy, Pandas, and Plotly for their awesome tools.

📄 License
This project is for educational purposes. If you adapt or build upon it, feel free to reference this repo. MIT License.

