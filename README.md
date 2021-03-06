# Pedestrian-and-traffic-signs-detection
<b>Project for 2019 Skoltech Intro to CV course<br>
Angelina Yaroshenko, Dinar Sharafutdinov, Dmitry Vypiraylenko</b>

Implementation of pedestrian and traffic signs detection using HOG + SVM with non-maxima suppression. We compared results with pretrained Faster R-CNN. Additionally, we trained a convolution neural net for traffic signs classification. As a training dataset, we've used<a href="http://oscar.skoltech.ru/"> Oscar dataset </a>. The specific thing about data is that it's winter pictures from the car. For positive samples, we've used <a href="http://graphics.cs.msu.ru/ru/node/1266">Russian Traffic Sign Dataset</a>, <a href="http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/">Caltech Pedestrian Detection Benchmark</a>, and <a href="http://benchmark.ini.rub.de/">German Traffic Sign Recognition Benchmark</a>

<b>Results</b>

Detection non-maxima suppression (without/with)
![Image](https://github.com/dinarkino/Pedestrian-and-traffic-signs-detection/blob/master/images/det-non-maxima-suppr.JPG)

Detection mistakes
<p align="center">
  <img width="800" height="500" src="https://github.com/dinarkino/Pedestrian-and-traffic-signs-detection/blob/master/images/det-mist.JPG">
</p>

Final traffic signs detection
<p align="center">
  <img width="460" height="300" src="https://github.com/dinarkino/Pedestrian-and-traffic-signs-detection/blob/master/images/sgn_gif.gif">
</p>

Final pedestrian detection<br>
<p align="center">
  <img width="460" height="300" src="https://github.com/dinarkino/Pedestrian-and-traffic-signs-detection/blob/master/images/gif_ppl.gif">
</p>

Faster R-CNN for pedestrian detection
<p align="center">
  <img width="600" height="400" src="https://github.com/dinarkino/Pedestrian-and-traffic-signs-detection/blob/master/images/frcnn.JPG">
</p>





