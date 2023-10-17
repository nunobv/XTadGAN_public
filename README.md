# XTadGAN
<h2> Generative Adversarial Networks to Detect Extremely Rare Anomalies </h2>

- Full Thesis Document [(PDF)](https://github.com/nunobv/XTadGAN_public/blob/main/XTadGAN%20-%20Dissertation%20-%20Final_Version.pdf) 
- Thesis Defense Presentation [(PDF)](https://github.com/nunobv/XTadGAN_public/blob/main/XTadGAN%20-%20Thesis%20Defense%20-%20NunoVasconcelos.pdf)

<br>
<h3>Abstract</h3>
Machine learning methods have been widely employed for anomaly detection in time series data,
but often struggle to identify rare anomalies in high-dimensional or non-stationary data. Generative Adversarial Networks (GANs) have shown promise in addressing this limitation, but their
effectiveness in detecting extremely rare anomalies remains a challenge. Additionally, the lack
of systematic comparison methods for evaluating anomaly detection algorithms, particularly in
relation to varying anomaly frequencies, has hindered progress in this field.
<br><br>
This thesis addresses these challenges by introducing novel contributions to the realm of
anomaly detection in time series data. Firstly, two new GAN-based architectures, TadGAN-DT
and XTadGAN, are proposed to handle scenarios with extremely rare anomalies. The former,
TadGAN-DT, incorporates non-parametric dynamic thresholding and pruning methods. The latter, XTadGAN, leverages meta-information on expected anomaly frequencies to establish raritybased dynamic thresholding and pruning strategies. Our experimental results demonstrate that
both algorithms outperform other relevant approaches in rare anomaly detection.
<br><br>
Furthermore, a comprehensive framework for evaluating anomaly detection models is introduced. This framework uses Monte Carlo sampling to generate an arbitrary number of time series
from a small set of original datasets, simulating various controlled scenarios. It enables systematic assessments across various time series attributes, specifically considering varying levels of
anomaly rarity. This establishes a standardized test bench, facilitating a deeper understanding of
model strengths and limitations. To enhance model comparisons, a novel sensitivity index, the
x-score, is introduced. This metric provides an objective measure to evaluate the performance
of different anomaly detection algorithms across a spectrum of attributes, particularly varying
anomaly frequencies.
<br><br>
This research contributes to the field of time series anomaly detection by advancing the understanding of rare anomaly detection using GANs. It introduces a robust framework for systematic
model evaluation, including a sensitivity index that enhances the reliability of model comparisons,
guiding future research and improving the applicability of anomaly detection algorithms in realworld scenarios.

<br>
<h3>Keywords</h3>
anomaly detection, time series, generative adversarial networks (GANs), TadGAN,
XTadGAN, rare anomalies, sensitivity analysis, evaluation framework, model comparison, Monte
Carlo sampling, rarity-based thresholding, dynamic thresholding
