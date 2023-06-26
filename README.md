<H1 align="center">Automatic Number Plate Detection and Recognition using YOLOv8</H1>

<h2 align="center">Run following commands in Google colab it will easy to run</h2>
## Steps to run Code

- Clone the repository
```
git clone https://github.com/monishkumar08/Automatic-number-plate-recognization-using-yolo-v8.git
```
- Goto the cloned folder.
```
cd Automatic-number-plate-recognization-using-yolo-v8
```
- Install the dependecies
```
pip install -e '.[dev]'

```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect
```


- Downloading a Sample Video from the Google Drive
```
gdown "https://drive.google.com/uc?id=1P-oVR0J35Dw40lzw47sE19oADSW-tyb1&confirm=t"

```

- Run the code with mentioned command below (For Licence Plate Detection and Recognition).
```
python predict.py model='best.pt' source='demo.mp4'

