# Automatic-Book-Digitaliser
The Automatic Book Digitaliser is a cost-effective, automated system designed to rapidly scan and digitize physical books with minimal human intervention. Developed as part of the TA212: Manufacturing Processes II course at IIT Kanpur, this project addresses the need for efficient preservation of ancient scriptures, fragile documents, and mandatory digital health records.

# Key Features
- **Dual-Arm Mechanism:** Employs a Page Lifter arm using reusable adhesive to separate pages and a Page Turning arm to flip them gently.

- **Integrated Control:** Powered by an Arduino UNO that executes a precise, timed cycle of mechanical movement and settling.

- **Automated Scanning:** Utilizes a Python-based automation script that listens for a "CAPTURE" signal from the Arduino to trigger a camera event via Bluetooth.

- **Digital Output:** Automatically compiles captured images into a single PDF document for easy archival and public access.

# System Architecture

The project integrates mechanical engineering, electronics, and software:

- **Mechanics:** Custom-fabricated mild steel frame and 3D-printed components (PLA).

- **Electronics:** Arduino-controlled servo motors for coordinated lifting and flipping.

- **Software:** Python scripts for serial communication and image capture synchronization.

~ Awarded as 2nd Best Project among all the Course Projects for TA212 in that Semester.

________________________________________________________________________________________________________________________

Developed by Group 25, 3rd Semester Y24, Under Guidance of Prof. Sarvesh Mishra, IIT Kanpur.
