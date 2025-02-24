# **PortPamper - Web-Based Port Scanner**  

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/Oura01/PortPamper)  

![Screenshot 1](https://raw.githubusercontent.com/Oura01/PortPamper/main/docs/s1.png)

PortPamper is a **web-based port scanner** that allows users to analyze target IPs or hostnames for open ports. It helps identify potential security vulnerabilities using **TCP/UDP scans**, **OS detection**, and **real-time progress tracking**. The application is built using **Flask (Python)** for the backend and **HTML, Tailwind CSS, and JavaScript** for the frontend.  

---

## **✨ Features**  
✔ **Port Scanning:** Scan IP addresses or hostnames for open ports using TCP or UDP.  
✔ **Real-Time Updates:** Displays live scan results with a progress bar.  
✔ **OS Detection:** Identify the operating system of the target.  
✔ **Downloadable Reports:** Export scan results as a **PDF** for offline use.  
✔ **User-Friendly Interface:** Simple, clean, and responsive UI.  
✔ **Error Handling:** Handles invalid inputs (e.g., incorrect IPs or port ranges).  
✔ **Scan Control:** Ability to cancel an ongoing scan.  

---

## **🛠️ Technologies Used**  
🔹 **Backend:** Flask (Python), Nmap, Multi-threading, Server-Sent Events (SSE).  
🔹 **Frontend:** HTML, Tailwind CSS, JavaScript, jsPDF.  
🔹 **Tools:** Git, Visual Studio Code, Nmap.  

---

## **📥 Installation**  

### **📌 Prerequisites**  
- **Python 3.x** installed  
- **pip** (Python package manager)   

### **🚀 Setting Up the Virtual Environment**  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/Oura01/PortPamper.git
   cd PortPamper
   ```

2. **Create and activate a virtual environment:**  
   - **Windows:**  
     ```bash
     python -m venv venv
     .\venv\Scripts\activate
     ```
   - **macOS/Linux:**  
     ```bash
     python -m venv venv
     source venv/bin/activate
     ```

3. **Install dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask application:**  
   ```bash
   python app.py
   ```

5. **Access the app in your browser:**  
   ```
   http://127.0.0.1:5000
   ```

---

## **📌 Usage Guide**  
1. Enter the target **IP address or hostname** in the input field.  
2. Select a **port range** (e.g., 1-100) and choose between **TCP or UDP scan**.  
3. Click **"Start Scan"** to begin.  
4. View **real-time results** with progress updates.  
5. Click **"Download Report"** to export the results as a **PDF**.  

---

## **🖼️ Screenshots**  
📌 **Home Page:**  
![Home Page](https://raw.githubusercontent.com/Oura01/PortPamper/main/docs/s1.png)  

📌 **Scan Results:**  
![Scan Results](https://raw.githubusercontent.com/Oura01/PortPamper/main/docs/s3.png) 

📌 **PDF Report:**  
![PDF Report](https://raw.githubusercontent.com/Oura01/PortPamper/main/docs/s2.png)

---

## **🙌 Acknowledgments**  
🔹 **Nmap** – Powerful port scanning engine.  
🔹 **Tailwind CSS** – Simple and flexible frontend framework.  
🔹 **Flask** – Lightweight and scalable backend framework.  


## **📬 Contact**  
For feedback or inquiries, reach out:  
📧 **Email:** hensikheni@web.de 
💼 **LinkedIn:** [Hensi Kheni](https://www.linkedin.com/in/hensi-kheni-527184289)  

---

## **📜 License** ![MIT License](https://img.shields.io/badge/License-MIT-green.svg)  
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  
