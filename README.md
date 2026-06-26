## Hi there, I'm Nazrin! 

I am an Electronics Engineering student specializing in **VLSI Design & Technology** with a strong passion for **Data Science, Analytics, and AI**. I like bridging the gap between cutting-edge software algorithms (like Machine Learning models) and hardware execution architectures (like FPGAs and SoC platforms).

---

### 🛠️ Tech Stack & Tools

- **Hardware & VLSI Architecture:** Verilog, Vivado, LTspice, Artix-7 FPGA, Pynq-Z2 (Zynq-7020)
- **Data Science & AI:** Python, PyTorch, Data Analytics, Time Series Forecasting, Machine Learning (CNNs)
- **Embedded Systems & Analog Simulation:** 8051 Microcontroller, Assembly/C, Proteus, LTspice, Keil uVision
- **Core Skills:** Competitive Programming, Data Structures & Algorithms (DSA), Digital Logic Design

---
---

### 🚀 Featured Projects

####  LeNet-5 CNN Hardware Inference Engine (MNIST)
*Designed and verified a hardware accelerator for handwritten digit recognition targeting the Xilinx Zynq-7020 SoC.*
- **Software Reference:** Trained a LeNet-5 CNN model in **PyTorch**, achieving a **98.99% classification accuracy** on 10,000 MNIST test images to extract baseline weights and biases.
- **RTL Architecture:** Implemented the full LeNet-5 pipeline (convolution, max-pooling, and fully-connected layers) using fully synthesizable **Verilog HDL**.
- **Hardware Optimization:** Integrated **8-bit fixed-point arithmetic** and a sequential **FSM-based pipeline controller** to optimize latency and hardware area constraints.
- **Synthesis & Verification:** Verified behavior via self-checking testbenches in **Vivado**. Synthesis results confirmed zero timing violations at a clock frequency of **50 MHz** on Artix-7 FPGA fabric.

#### 📈 Amazon Stock Price Time Series Forecasting
*Data Science & Analytics Internship Project at Zidio Development.*
- **Data Pipeline:** Automated historical stock data collection from Yahoo Finance utilizing the `yfinance` API.
- **Data Preprocessing:** Performed exploratory data analytics (EDA) and engineered **7-day and 30-day rolling averages** to smooth out market volatility and identify core trends.
- **Comparative Modeling:** Evaluated and deployed three distinct predictive paradigms to forecast stock trajectories for a 30-day forward horizon:
  - *Prophet:* For time-aware seasonal forecasting.
  - *ARIMA:* For classical statistical modeling.
  - *LSTM (Deep Learning):* Implemented in **TensorFlow** for sequence and temporal dependencies.
- **Tech Stack:** Python, Pandas, Matplotlib, TensorFlow, Statsmodels, Prophet.

#### ⏱️ Digital Logic & FPGA Implementations
*A collection of hardware designs focused on timing constraints, control logic, and RTL verification.*
- **Digital Stopwatch:** Designed a **`mm:ss` digital stopwatch** logic in Verilog using clock dividers and state machines to manage start, split-time, and reset actions.
- **Core Digital Blocks:** Implemented and tested foundational hardware architectures including an **FPGA Counter**, a **Magnitude Comparator**, and a **Sequence Detector**.

#### 📟 8051 Digital Multi-waveform Generator
*Engineered an embedded firmware system to generate precise electrical wave signals.*
- **Hardware Stage:** Simulated an interface in **Proteus** incorporating an **8051 Microcontroller** routing data to a **DAC0808** digital-to-analog converter and an **LM741** op-amp filtering stage.
- **Firmware Core:** Programmed the microcontroller (Assembly/C inside Keil uVision) to generate adjustable Sine, Triangle, and Square waveforms.


---

### 📈 Current Focus & Goals
-  Designing and optimizing hardware accelerators for deep learning models (TinyML & Edge AI).
-  Expanding my toolkit in data analytics pipelines and advanced statistical forecasting.
-  Aspiring to pursue opportunities in the intersection of microelectronics and intelligent systems.

---

### Connect with me
- 💼 [LinkedIn](https://www.linkedin.com/in/nazrin-m-n)
- 📧 [Email](nazrinmn01@gmail.com)
