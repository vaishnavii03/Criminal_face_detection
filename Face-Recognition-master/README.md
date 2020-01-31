# FaceRecognition

Machine Learning project to recognise people from an Image just like facebook.

Built with the help of [dlib's](http://dlib.net/) state-of-the-art face recognition built with deep learning.
The model has an accuracy of 99.38% on the [Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) benchmark.

## Dependencies:

- Python 3.x
- Numpy
- Scipy
- [Scikit-learn](http://scikit-learn.org/stable/install.html)
- [dlib](http://dlib.net/)

    Tip: Installing dlib can be a tedious job. On macOS or Linux you may follow [this link](https://gist.github.com/ageitgey/629d75c1baac34dfa5ca2a1928a7aeaf).

- Extras:

    - OpenCV (required only in `webcam.py` for capturing frames from the webcam)

    - For using `./demo-python-files/projecting_faces.py` you will need to install [Openface](https://cmusatyalab.github.io/openface/setup/).

        To install Openface, follow the below instructions:
        ```bash
            $ git clone https://github.com/cmusatyalab/openface.git
            $ cd openface
            $ pip install -r requirements.txt
            $ sudo python setup.py install
        ```

