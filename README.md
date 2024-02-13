# Utils
Utils for All Modules

#### ISLVRC : <br>
```
wget https://image-net.org/data/ILSVRC/2012/ILSVRC2012_img_val.tar -O ILSVRC2012_img_val.tar
wget https://image-net.org/data/ILSVRC/2012/ILSVRC2012_img_test_v10102019.tar -O ILSVRC2012_img_test_v10102019.tar
wget https://image-net.org/data/ILSVRC/2012/ILSVRC2012_devkit_t12.tar.gz -O ILSVRC2012_devkit_t12.tar.gz
wget https://raw.githubusercontent.com/mlcommons/inference_results_v3.1/main/closed/Intel/code/resnet50/pytorch-cpu/val_data/val_map.txt -O val_map.txt
```

#### MLCommons Calibration : <br>
```
wget https://raw.githubusercontent.com/mlcommons/inference/master/calibration/ImageNet/cal_image_list_option_1.txt -O cal_image_list_option_1.txt
```

#### COCO 2017 Validation Dataset :
```
wget http://images.cocodataset.org/zips/val2017.zip
wget http://images.cocodataset.org/annotations/annotations_trainval2017.zip
```

#### Jupyter Notebook 
```
apt-get update
apt-get install vim git -y
pip install jupyter
pip install --upgrade notebook==6.4.12
pip install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
pip uninstall traitlets
pip install traitlets==5.9.0
jupyter notebook --ip="*" --allow-root
```
