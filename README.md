<center>
  <!-- Project Title -->
  <h1 align ="center"><br>Image Denoising Pipeline (Classical Methods)</h1>
  <p style="max-width: 700px; font-size:16px; color:#444;">
    A professional Python-based pipeline for adding noise to grayscale images and denoising them
    using classical methods. Evaluate and compare results using PSNR and SSIM metrics,
    with automatic visualization and CSV output.
  </p>
  
  <!-- Horizontal Badges -->
  <p align ="center">
    <img src="https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white" alt="Python Badge" style="margin:5px;">
    <img src="https://img.shields.io/badge/OpenCV-4.8-blue?logo=opencv&logoColor=white" alt="OpenCV Badge" style="margin:5px;">
    <img src="https://img.shields.io/badge/Matplotlib-3.8-orange?logo=matplotlib&logoColor=white" alt="Matplotlib Badge" style="margin:5px;">
    <img src="https://img.shields.io/badge/Pandas-2.1-blue?logo=pandas&logoColor=white" alt="Pandas Badge" style="margin:5px;">
    <img src="https://img.shields.io/badge/License-MIT-green" alt="License Badge" style="margin:5px;">
  </p>
  <br>
</center>


<center>
<h2 align ="center"><br>Table of Contents</h2>
</center>
<br>
<ul>
  <li><a href="#overview">Overview</a></li>
  <li><a href="#features">Features</a></li>
  <li><a href="#folder-structure">Folder Structure</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#evaluation-metrics">Evaluation Metrics</a></li>
  <li><a href="#license">License</a></li>
</ul>

<center>
<h2 align ="center"><br id="overview">Overview</h2>
</center>
<br>
<p>
This project implements a **professional Python-based Image Denoising Pipeline** using classical techniques. It allows adding Gaussian noise to grayscale images, denoising them using multiple classical methods, and evaluating the results with standard metrics. Fully reproducible, results are automatically saved and visualized.
</p>

<center>
<h2 align ="center"><br id="features">Features</h2>
</center>
<br>
<ul>
  <li>Add Gaussian noise to images</li>
  <li>Denoising with Gaussian Blur, Median Filter, Non-Local Means (NLM)</li>
  <li>Evaluation using PSNR and SSIM</li>
  <li>Automatic CSV output of all metrics</li>
  <li>Visual comparison of results with plots</li>
  <li>Organized folder structure for reproducibility</li>
</ul>

<center>
<h2 align ="center"><br id="folder-structure">Folder Structure</h2>
</center>
<br>
<pre>
Image-Denoising-Pipeline/
├─ denoising.py           # Main pipeline script
├─ requirements.txt       # Dependencies
├─ README.md              # Project documentation
└─  results/               # Denoised images and CSV
   └─ denoising_results.csv

</pre>

<center>
<h2 align ="center"><br id="installation">Installation</h2>
</center>
<br>
<p>Clone the repo and install dependencies:</p>
<pre>
git clone https://github.com/hamaylzahid/Classical-Image-Denoising-Pipeline.git
cd Classical-Image-Denoising-Pipeline
pip install -r requirements.txt
</pre>

<center>
<h2 align ="center"><br id="usage">Usage</h2>
</center>
<br>
<p>Run the denoising pipeline:</p>
<pre>
python denoising.py
</pre>
<p>During execution:</p>
<ul>
  <li>Provide a path to a grayscale image when prompted</li>
  <li>Denoised images are saved in <code>results/</code></li>
  <li>PSNR and SSIM metrics are saved in <code>denoising_results.csv</code></li>
  <li>Plots comparing all images are displayed automatically</li>
</ul>

<center>
<h2 align ="center"><br id="evaluation-metrics">Evaluation Metrics</h2>
</center>
<br>
<ul>
  <li><b>PSNR (Peak Signal-to-Noise Ratio)</b> — Higher values indicate better denoising</li>
  <li><b>SSIM (Structural Similarity Index)</b> — Measures perceptual similarity; 1.0 is perfect</li>
</ul>

<br>
<p>Example metrics saved in <code>denoising_results.csv</code>:</p>
<pre>
          PSNR      SSIM
Noisy     22.60     0.36
Gaussian  18.83     0.76
Median    19.43     0.57
NLM       25.39     0.68
</pre>

<center>
<h2 align ="center"><br id="license">License</h2>
</center>
<br>
<p>
<img src="https://img.shields.io/badge/License-MIT-green" alt="License Badge"><br>
This project is licensed under the MIT License.
</p>
