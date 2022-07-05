# DeblurGANV2_modified 
## Installion
- Download pre-trained models: [fpn_inception.h5](https://drive.google.com/uc?export=view&id=1UXcsRVW-6KF23_TNzxw-xC0SzaMfXOaR) </br>
  | - Move file fpn_inception.h5 to directory models/
- Download file .pth: [inceptionresnetv2](https://drive.google.com/uc?id=1y6GeaoWjhqjRjrXuZvCYEQYlblZGkE6X) </br>
  | - Move file .pth to directory checkpoints/'
## Usage
- To test on a single image. </br>
```
python predict.py IMAGE_NAME.jpg
```
## Requirement
- Create virtual enviroments and run file requirements.txt to automatic install required package
