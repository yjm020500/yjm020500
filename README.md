<!-- 헤더 배너 -->
<p align="center">
 <img src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0D47A1&text=Welcome%20to%20my%20GitHub!&section=header&fontSize=64&fontAlign=50&fontColor=FFFFFF&animation=fadeIn" />
</p>

<!-- 간단 소개 -->
<p align="center">
  <strong>안녕하세요! 윤종민입니다.</strong> <br/>
</p>

<!-- 연락처 / 링크 -->
<h3 align="center">📬 Contact</h3>
<p align="center">
  <a href="mailto:yjm020500@naver.com">
    <img src="https://img.shields.io/badge/yjm020500@naver.com-126304?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/yjm020500" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.notion.so/25b19abd498f808088f6ec4987859b47" target="_blank">
    <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white" alt="Notion"/>
  </a>
</p>

---

## 💻 Tech Stacks
<!-- 언어/알고리즘 -->
<p>
  <img src="https://img.shields.io/badge/Verilog-6857F7?style=flat-square&logo=verilog&logoColor=white" alt="Verilog"/>
  <img src="https://img.shields.io/badge/SystemVerilog-1F0A8A?style=flat-square&logo=verilog&logoColor=white" alt="SystemVerilog"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C"/>
  <img src="https://img.shields.io/badge/MATLAB-D45B15?style=flat-square&logo=matlab&logoColor=white" alt="MATLAB"/>
</p>

<!-- 툴/플랫폼 -->
<p>
  <img src="https://img.shields.io/badge/Xilinx%20Vivado-FF6F00?style=flat-square&logo=xilinx&logoColor=white" alt="Vivado"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white" alt="Notion"/>
</p>

---

## 🚀 Projects
| 프로젝트<br> (Project) | 설명<br> (Description) | 수행기관 (Organization) | 링크<br> (Links) |
|:---|:---|:---|:---|
| **영상 처리를 활용한 <br>Penalty Kick Game** <br> 📅(25.09.03~25.09.30) | - **AXI4-Lite 인터페이스를 기반**으로 직접 설계한 **하드웨어 &nbsp;&nbsp;&nbsp;IP**(BTN, UART, SCCB, VGA)를 연결하여 **SoC구조 구성**<br> -완성한 SoC 구조를 **임베디드 코딩**으로 제어<br> - UART 통신 및 PC와 FPGA간의 **통신 프로토콜 정의**<br> - **OV7670 카메라**에서 **VGA 디스플레이**로의 다양한<br>&nbsp;&nbsp;&nbsp;이미지 필터 구현 및 **SystemVerilog**를 통한 검증<br> - 1인 플레이 모드와 2인 플레이 모드로 구성 | 대한상공회의소<br>서울기술교육센터 | [영상 처리를 활용한<br> Penalty Kick Game](https://github.com/71105673/Ronaldo_Project) |
| **512 Point FFT<br> Module Design** <br> 📅(25.07.17~25.08.05) | - **MATLAB**을 활용해 **Radix-2 FFT**의 구조 이해<br> - **Floating-Point**와 **Fixed-Point** 분석<br> - **CBFP** 적용을 통한 SQNR 비교 <br> - **소프트웨어 모델링** 기반 **하드웨어 모듈** 설계<br> - **Synopsys EDA Tool**을 이용해 **RTL, Gate Level 합성 <br>&nbsp;&nbsp;&nbsp;및 결과 분석**<br> - **Vivado를 활용한 Simulation과 Bitstream**생성<br> - 알고리즘부터 **RTL 설계**, **Synthesis**, **FPGA Bitstream**<br>&nbsp;&nbsp;&nbsp;생성까지 전반적인 **Front-End** 과정 학습<br> | 대한상공회의소<br>서울기술교육센터 | [FFT Design](https://github.com/EunSeongL/FFT-Design) |
| **Mathtutor** <br> 📅(25.07.01~25.07.11) | - 문제를 찍으면, **AI가 자세한 풀이와 설명**을 해주는 <br>&nbsp;&nbsp;&nbsp;수학 튜터<br> - 수식 이미지 캡처 및 **Mathpix OCR** 인식<br> - **SymPy를 통한 수식 계산**<br> &nbsp;&nbsp;&nbsp;(정적분, 미분, 방정식, 푸리에 변환)<br> - **Speech Rule Engine**을 이용한 수식 음성 해석<br> - **gTTS** 기반 음성 출력<br> - **Ollama 기반 LLM** (Gemma 3:12b) 풀이 생성 | 대한상공회의소<br>서울기술교육센터 | [Mathtutor](https://github.com/yjm020500/Team6_mathtutor) |
| **Digital Watch<br> Multi Sensor Interface** <br> 📅(25.05.20~25.06.02) | - **Basys3 FPGA 보드**를 이용해 **WATCH & STOPWATCH**,<br> &nbsp;&nbsp;&nbsp; **UART 통신**, **초음파 센서(HC-SR04)와<br> &nbsp;&nbsp;&nbsp;온습도 센서(DHT11) 인터페이스**통합 제작 <br> - **각 모듈을 블록화**하여 Top Module에서 인스턴스하여<br> &nbsp;&nbsp;&nbsp;설계<br> - FND와 버튼, UART를 이용하여 Watch/Stopwatch 및<br> &nbsp;&nbsp;&nbsp;센서 interface를 조정하고, Switch를 사용하여<br> &nbsp;&nbsp;&nbsp;네 가지 mode로 변경 가능 | 대한상공회의소<br>서울기술교육센터 | [Digital Watch<br> Multi Sensor Interface](https://github.com/yjm020500/Digital_Watch_Multi_Sensor_Interface) |
| **Project Z :<br> 연구소 탈환 작전** <br> 📅(25.04.25~25.05.07) | - **ARM Cortex-M3** 기반의 STM32 마이크로컨트롤러로<br> &nbsp;&nbsp;&nbsp;FSM 제어 구조의 게임 로직 구현 및<br> &nbsp;&nbsp;&nbsp;**하드웨어 데이터시트 기반 레지스터 직접 제어**<br> - 타이머, GPIO, 인터럽트 등 **데이터시트를 참고하여<br> &nbsp;&nbsp;&nbsp;필요한 기능들의 레지스터 비트를 직접 활성화**하고 활용<br> - **임베디드** 환경에서 **레지스터 제어와 인터럽트 기반**<br> &nbsp;&nbsp;&nbsp;프로그래밍 이해<br> - 두 개의 각각 **다른 역할을 하는 STM32 보드**를<br> &nbsp;&nbsp;&nbsp;이용하였으며, **두 보드간 UART 통신**으로 데이터 교환 | 대한상공회의소<br>서울기술교육센터 | [GameProject_ProjectZ](https://github.com/yjm020500/GameProject_ProjectZ) |
| **FPGA를 이용한 실시간 영상 처리** <br> 📅(24.11.01~24.12.12) | - **JFK-200A FPGA 보드(qa~~)와OV7670 카메라 모듈, &nbsp;&nbsp;&nbsp;VGA666 GPIO to VGA 컨버터**를 사용하여 실시간으로<br> &nbsp;&nbsp;&nbsp;영상 처리<br> - OV7670으로 받은 영상을 키패드를 통해 선택한 필터로<br> &nbsp;&nbsp;&nbsp; 처리하여 **GPIO 출력**<br> - 선택한 필터 번호는 **7-segment로 표시**<br> - 출력된 **GPIO 신호는** VGA666 컨버터를 통해 **VGA 신호로**<br> &nbsp;&nbsp;&nbsp; 바뀌고, **HDMI 컨버터로 최종 변환**되어 모니터에 입력 | 숭실대학교 | [FIR filter system](https://github.com/yjm020500/FIR_Filter_System) |
| **Memory Management Simulator** <br> 📅(24.05.07~24.06.13) | - **메모리 [ Paging ] 개념을 구현**하고자 하였으며 paging<br> &nbsp;&nbsp;&nbsp; 구현을위해 필요한 **자료구조와 이를 제어하는 함수,<br> &nbsp;&nbsp;&nbsp; 알고리즘**을 제작<br> - minios 프로그램 상에서 64KB 메모리 공간을 할당 받아 <br> &nbsp;&nbsp;&nbsp; 이를 **Paging** 기법 구현을 위한**Physical Memory<br> &nbsp;&nbsp;&nbsp; (Dummy)** 로 사용<br> - 실행하고자 하는 프로그램을 읽어 **Page 단위로 나누고<br> &nbsp;&nbsp;&nbsp; Page Manager를 세팅**하여 메모리에 적재하면<br> &nbsp;&nbsp;&nbsp; **Program Monitor에서 이 프로그램의 실행** 확인<br> | 숭실대학교 | [Memory Management Simulator](https://github.com/SSUminiOS/B1teamOS) |
| **FIR filter system** <br> 📅(23.10.30~23.12.04) | - **Sobel 필터**를 통한 필터링으로 FHD 이미지를<br> &nbsp;&nbsp;&nbsp; **edge detection**<br> - 필터링이 이루어지는 **Calculation block**은 <br> &nbsp;&nbsp;&nbsp; **Core FSM에 의해 컨트롤**<br> - 필터의 **특정 부분**이나 **필터 자체**를 **병렬**로 두어<br> &nbsp;&nbsp;&nbsp; 속도 차이를 확인<br> - 이미지를 읽어와 필터 처리 후 다시 이미지로 저장 | 숭실대학교 | [FIR filter system](https://github.com/yjm020500/FIR_Filter_System) |

---


<p align="center">
  꾸준히 만들고, 끝까지 검증합니다. <br/>
  <em>“작동하는 하드웨어가 최고의 증명.”</em>
</p>
