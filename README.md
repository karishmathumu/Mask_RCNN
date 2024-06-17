pip install opencv-python
python
>>>import cv2 as cv
>>>print(cv.__Version__)
>>>4.10.0
>>>exit()
cd Mask_RCNN
python mask_rcnn.py --image /path/to/test_image.jpg --device cpu
pip uninstall opencv-python
pip install opencv-python-headless
pip uninstall opencv-python--headless -y
pip install opencv-python --upgrade
>>>python mask_rcnn.py --image /path/to/test_image.jpg --device cpu   results saved to Mask_RCNN/..mask_rcnn_out_py.jpg
>>>python mask_rcnn.py --video /path/to/test_video.mp4 --device gpu   results saved to Mask_RCNN/..mask_rcnn_out_py.avi
