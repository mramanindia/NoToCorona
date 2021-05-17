<h1>NoToCorona</h1><hr>
This time of uncertainty has impacted the lives of millions and I was one of them.<br>
Being in quarantine desperately, I was looking for some solutions that can stop the spread of coronavirus and came to the idea of Building NoToCorona project.<br>
NoToCorona project uses Deep learning and Computer vision to detect 
Humans, Check the mask on face, Check the body temperature, and notifies to the operator with an alarm.

<h2>How does it work?</h2>
NoToCorona takes input from the webcam and then breaks it into frames.
After breaking into frames, it uses <code>OpenCV</code> to detect wheater the input coming is of a human face or not.
As it matches that its Human face, It uses deep learning trained model to detect whether the person has wear a mask or not. 

After identifying and conforming, it opens a new tab where the output is visible with a label, "With Mask" or "Without Mask".

<h3>Technology used</h3>
<ul>

<li>Deep learning</li>
<li>Python</li>
<li>Opencv</li>
<li>Tensorflow</li>
<li>Keras</li>
</ul>
<h2>Setup</h2>
To run this project on your pc, Clone it to your repository and then download it to your local machine.<br>
Before running the <code>detect_mask.py</code> check wheather you have upgraded version of python install in you pc orr not.
Moreover, you needed some libraries installed in your pc.
<h3> Liabraries</h3>
<ul>
<li><code>pip install --upgrade pip
</code></li>
<li><code>pip install pandas
</code></li>
<li><code>pip install tensorflow
</code></li>
<li><code>pip install numpy
</code></li>
<li><code>pip install opencv-python
</code></li>
<li><code>pip install imutils
</code></li>
  <li><code>pip install playsounds
</code></li>
  <li><code>pip install tk
</code></li>
</ul>

<h2>Where does this project can be used</h2>
<ul> <li>
  It can be used in the Malls at the entrance </li>
  <li>It can be used in the schools to monitor  kids, or at any teaching place</li>
  <li>It can be used at crowded public place</li>
  <li> And it can be used at any place which is crowded and need special attention</li>
  
</ul>

<h2>Best benifits of NoToCorona</h2>
My Intention in making this project was to protect the front liners from direct Interaction in all possible ways. 
Decrease the spread of the Virus and protect everyone.

<strong>Well, this project is an evolutionary project that can be featured up and can be used in automatic gates and more.</strong>

<h3>Reference I taken to make this project</h3>
I have taken refrence from Balaji Srinivasan project of mask detection and used his dataset to train my model. A great shout otu to him.
His repository <code>https://github.com/balajisrinivas/Face-Mask-Detection</code>







