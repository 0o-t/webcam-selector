# webcam-selector
複数のwebカメラから顔が正面を向いている映像を自動的に選択できます。

## Requirement
- Python3
- opencv-python
- dlib
- dlib学習済みモデル(shape_predictor_68_face_landmarks.dat)
- imutils
- numpy

## Preparing
```
pip install opencv opencv-contrib dlib numpy
wget http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
tar jxvf shape_predictor_68_face_landmarks.dat.bz2
```
## Usage
- webcam-selector.pyを実行すると、顔が正面を向いているwebカメラの映像が表示されます。
- 選択したカメラの映像を仮想webカメラとして送信できます (開発中）
- GUIから使用するwebカメラの選択や、画面が切り替わるまでの時間の調整ができます（開発中）
## Note
- 本ソフト起動時、映像が表示されるまでに数十秒の時間がかかります。
