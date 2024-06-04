# jetbot Nano 영상처리를 활용한 AI 무인운반차량 제작

### Smart Factory with AGV Robot
반도체 8대 공정 중, 웨이퍼 제조 / 산화 공정 / 포트 공정 / 패키징 공정을 구현 <br/>
로봇과 라즈베리파이는 DB와 폴링 방식으로 연결되며, 현재 로봇의 위치와 상태 정보를 지속적으로 Read/Write 함. <br/>
로봇은 길을 따라서 주행하면서, 사전에 정해진 목표 영역까지 주행 함<br/>

### 사용된 기술 및 장비
AGV Robot : Nvidia Jetson Nano 보드 기반의 AGV 로봇<br/>
Raspberry Pi 5 : 라즈베리파이 5, 주변장치(esp32)와 Robot 사이의 미들웨어 역할을 수행<br/>
ESP 32 : 소형 IoT기기에 탑재하기 위한 무선 통신 컨트롤러 장치, 라즈베리파이로 부터 MQTT 메시지를 받으면 각 공정(모터 드라이버, 수증기 모듈 등)을 제어<br/>

### 프로그램 모식도
![image](https://github.com/Hojun1123/jetbot_Project/assets/65999992/950410a4-728e-48d3-a4fd-b8cf1de4c15a)


###### NVDIA와 Wareshare에서 제공하는 Sample Code
- [https://github.com/NVIDIA-AI-IOT/jetbot] <br/>
- [https://github.com/waveshare/JETANK?tab=readme-ov-file]


### Auto Driving Mode
![image](https://github.com/Hojun1123/jetbot_Project/assets/65999992/5e7e8628-098d-40b3-9d85-247ca9b0304b)

### 실행 영상
https://github.com/Hojun1123/jetbot_Project/assets/65999992/0f6c5253-487f-4d59-84a9-e2fe84360400



