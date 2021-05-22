# traffic-sign
## Dataset
Download at: https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign
Unzip in /data

## Dependencies
pip install -r requirements.txt

## Neural Network training
python train.py --dataset data --model output/trafficsignnet.model --plot output/plot.png

## Prediction
python predict.py --model output/trafficsignnet.model --images data/Test --examples examples
