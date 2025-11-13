# Signal Visualizer & Digital/Analog Converter

This project is an **interactive tool** for visualizing **digital and analog signals**.  
It allows users to explore various **digital encoding schemes**, **analog sine waves**, and **sampling & quantization** concepts with real-time plots.  

The tool is built using **Python**, **NumPy**, **Matplotlib**, and **ipywidgets**, making it suitable for **learning and teaching signal processing concepts**.

---

## 🚀 Features

### Digital Signal Conversions
- Unipolar NRZ  
- Polar NRZ  
- RZ  
- Manchester  
- Differential Manchester  
- Bipolar AMI  
- Visualize encoded signals based on user-input bit sequences  

### Analog Signal Operations
- Generate a sine wave with specified frequency, amplitude, and duration  
- Sample and quantize analog signals  
- Visualize reconstructed signals after quantization  

### Interactive UI
- Dropdown menus and text inputs for easy parameter entry  
- Real-time plotting using Matplotlib  
- Runs in **Jupyter Notebook / Google Colab**  

---

## ⚙️ How to Use

1. Open the notebook in **Google Colab** or **Jupyter Notebook**.  
2. Use the dropdown to select **Digital Conversion** or **Analog Conversion**.  
3. For **digital signals**:
   - Enter the bit sequence (e.g., `10110`)  
   - Select the encoding scheme  
   - Click **Run** to see the plot  

4. For **analog signals**:
   - Choose **Generate Sine** or **Sample & Quantize**  
   - Enter parameters as `freq,amp,duration` (e.g., `5,1,1`)  
   - Click **Run** to see the waveform  

---

## 🖼️ Example Output

- Digital waveform plots for different encoding schemes  
- Sine wave generation and sampling plots  
- Reconstructed signals after quantization  

---

## 🧑‍💻 Technologies Used

- **Python 3**  
- **NumPy**  
- **Matplotlib**  
- **SciPy**  
- **IPyWidgets** (for interactive UI)  

---

## 📚 Learning Outcomes

- Understand **digital signal encoding techniques**  
- Learn about **analog signal generation and sampling**  
- Explore **quantization and reconstruction**  
- Gain hands-on experience with **interactive Python visualizations**

---

## ⚡ Run Locally

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
