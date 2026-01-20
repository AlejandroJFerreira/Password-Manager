# Password-Manager

• Built a full-stack password manager as part of a team at UOttahack 8 with a Java Spring Boot API, web frontend, and Raspberry Pi backend.

• Designed REST endpoints to encrypt credentials server-side and securely forward them to a dedicated hardware vault.

• Implemented a Flask service on Raspberry Pi to store and retrieve encrypted credentials per service.

• Coordinated rapidly with teammates to integrate components and deliver a functional end-to-end system under time constraints.

Components:
-----------

Front-End + Java API = https://github.com/AlejandroJFerreira/VikIsDownstairs

Python Reciever Back-End = https://github.com/AlejandroJFerreira/minjun

Steps to Turn On:
-----------------

1. Connect SSH with Raspberry Pi 5 (with QNX 8) and install all necessary prerequisites including QNX SDP 8.0 on computer.
2. Open Terminal #1 and navigate to the folder with pi_receiver.py. Turn it on via 'python3 pi_receiver.py'.
3. Open Terminal #2 and navigate to the VikIsDownstairs folder with the mvnw. Turn it on via '.\mvnw.cmd spring-boot:run'.
4. Run the Front-End via 'http://localhost:8080/'.
