NU-Information-Exchange-System-CN-Project
/ ├── README.md ├── server/ │ ├── server.cpp │ └── build_instructions.txt ├── client_gui/ │ ├── ClientGUI source files │ └── screenshot.png ├── admin_gui/ │ ├── AdminGUI source files │ └── screenshot.png ├── packet_tracer_topology/ │ ├── NU_WAN.pkt │ └── topology_diagram.png ├── project_video/ │ └── CN_Project_Demo.mp4 ├── report/ │ └── LAB_PROJECT_REPORT_CN.pdf │ └── Self_Evaluation.pdf └── LICENSE (optional)

NU-Information Exchange System — TCP + UDP Multi-Campus Communication Network

A FAST-NUCES Computer Networks Semester Project (Fall 2025)

Description

This project implements a full multi-campus communication system using a hybrid TCP + UDP networking model. Campuses like Lahore, Karachi, CFD, Multan, Islamabad, and Peshawar connect to a central server, exchange messages, send heartbeats, and receive admin broadcasts.

Includes:

👉 C++ multi-threaded server

👉 Qt-based GUI Clients

👉 Qt Admin Monitoring Dashboard

👉 Cisco Packet Tracer WAN topology (RIPv2 dynamic routing)

👉 Full documentation + video demo

Based on our lab project requirements and report

LAB_PROJECT_REPORT_CN

.

Features

✔ TCP-based authentication and messaging ✔ UDP heartbeat monitoring ✔ Admin broadcast system ✔ Real-time active campus table ✔ Multi-threaded server ✔ GUI client for each campus ✔ RIPv2 dynamic routing in Packet Tracer ✔ Full topology simulation

How to Run

Server (Ubuntu):

g++ server.cpp -std=c++17 -pthread -o server_app ./server_app

Client GUI (Qt): Open Qt Creator → Build → Run

Admin GUI (Qt): Open Qt Creator → Build → Run

Contributors

Sara Shakeel – 23F-0617

Hajra Haseeb – 23F-0789

Laiba Khalid – 23F-0784

Instructor: Sir Hassan Ahmad (FAST-NUCES)
