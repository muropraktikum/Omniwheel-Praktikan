Library Used In the Project : 

| Library | Link |
| ------ | ------ |
| Flask | https://flask.palletsprojects.com/en/2.2.x/installation/|
| OpenCV | https://pypi.org/project/opencv-contrib-python/ |
| Imutils | https://pypi.org/project/imutils/ |
| Numpy | https://pypi.org/project/numpy/ |
| netifaces  | https://pypi.org/project/netifaces/|
|  threading  | https://pypi.org/project/threaded/|

> Note: Link diatas merupakan dokumetasi resmi. Silahkan dikunjungi untuk menambah wawasan.


<h2>🧐 Troubleshoot </h2>
<p>Jika Mengalami error seperti dibawah :  </p>

``` bash
Traceback (most recent call last):
  File "/home/pi/OmniWheels/start.py", line 1, in <module>
    import cv2
ModuleNotFoundError: No module named 'cv2'
```

<p> Solusinya adalah kalian harus menginstall cv2 (OpenCV). berikut command untuk menginstall cv2 </p>
  
  ``` bash
sudo apt-get install python3-pip
```

<p>Jika Mengalami error seperti dibawah :  </p>

``` bash
Traceback (most recent call last):
  File "/home/pi/OmniWheels/start.py", line 2, in <module>
    import imutils
ModuleNotFoundError: No module named 'imutils'
```
<p> Solusinya adalah kalian harus menginstall imutils. berikut command untuk menginstall imutils </p>
  
  ``` bash
sudo pip3 install imutils
```
<p>Jika Mengalami error seperti dibawah :  </p>

``` bash
Traceback (most recent call last):
  File "/home/pi/OmniWheels/start.py", line 9, in <module>
    import netifaces as ni
ModuleNotFoundError: No module named 'netifaces'
```
<p> Solusinya adalah kalian harus menginstall netifaces. berikut command untuk menginstall netiface </p>
  
  ``` bash
sudo pip3 install netifaces
```
