# boostcamp_pstage10

# Environment
## 1. Install dependencies
```
pip install -r requirements.txt
```

# Run
## 0. symbolic link
ln -s code_t2045 code
<br>
## 1. train
python train.py  (default)
<br>
or
<br>
python train.py --model_config ${path_to_model_config} --data_config ${path_to_data_config}

## 2. inference(submission.csv)
python inference.py (default)
<br>
or
<br>
python inference.py --model_config configs/model/mobilenetv3.yaml --weight exp/2021-05-13_16-41-57/best.pt --img_root /opt/ml/data/test --data_config configs/data/taco.yaml3


# Reference
Our basic structure is based on [Kindle](https://github.com/JeiKeiLim/kindle)(by [JeiKeiLim](https://github.com/JeiKeiLim))
