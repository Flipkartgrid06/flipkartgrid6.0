
# **Product Detection and Liveness Using YOLOv8**

## **Overview**
This project implements **Product Detection** using **Ultralytics YOLOv8** to detect various products in a live video feed. It also integrates a secondary model to monitor the **liveness of fruits and vegetables** based on their freshness or spoilage. The dashboard displays product details, tracks product counts, and handles predictions in real-time.

**Team name : OUROBOROS**
## **Team Members**
- **Santhosh K** (Team Leader)
- **Saravanan S**
- **Siddarth J N**
- **Geetha T**
- **Logesh S**

## **Technologies Used**
- **YOLOv8 (Ultralytics):** For product detection.
- **Flask:** Backend framework to serve video feeds and handle detection requests.
- **PostgreSQL:** (Previously used) To fetch product details based on class names.
- **JavaScript:** For managing countdown timers, real-time updates, and handling user interactions on the front end.
- **CSS & HTML:** For styling and structuring the user interface using flexbox layout.
- **Python:** Backend scripting, integrating models, and handling API requests.

## **Installation and Setup**

### **Pre-requisites**
- Python 3.x
- YOLOv8 (Ultralytics) installed
- Flask
- PostgreSQL (optional for retrieving product details)

### **Steps**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Flipkartgrid06/flipkartgrid6.0.git
   cd flipkartgrid6.0
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up YOLOv8 Model:**
   Place the trained YOLOv8 model in the appropriate directory.

4. **Run Flask Application:**
   ```bash
   python app.py
   ```

5. **Access the Dashboard:**
   Open your browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

---
