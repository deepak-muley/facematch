# facematch
Face match in python using Facenet and their pretrained model


#http://www.python36.com/face-detection-matching-using-facenet/
virtualenv venv27
. ./venv27/bin/activate
git clone https://github.com/deepak-muley/facematch.git
cd facematch
pip install -r requirements.txt
export PYTHONPATH=$PYTHONPATH:$(pwd)
python face_detect_demo.py --img=images/faces.jpg
