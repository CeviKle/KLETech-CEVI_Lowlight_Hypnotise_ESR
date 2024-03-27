# Efficient SRGAN for super-resolution of images

## To download the repository 
```bash
git clone https://github.com/CeviKle/KLETech-CEVI_Lowlight_Hypnotise_ESR.git
cd KLETech-CEVI_Lowlight_Hypnotise_ESR
```
## To test the model
Place your own **low-resolution images** in `./LR` folder
set path of LR images to  ```test_img_folder``` variable in teh ```test.py``` file
Place the models in `./models`, and then run,

```bash
python test.py
```
The results are stored in `./results` folder.