# Attention-Guided-Two-Stage-Infrared-and-Visible-Image-Fusion-Framework

Suggesting run on Google Colab (Using GPU). Because all of paths coded for colab. If you use your pc to run it. You have to download the dataset from "https://www.kaggle.com/datasets/monishshrivastava1/llvip-dataset".

When you open in the colab you have to upload your kaggle api json file for download dataset. (You have to just paste the folder path in first code block).

After you have to upload checkpoints folder in colab machines content folder. Pathway should be like this ;

```
content
  ├── checkpoints
  |   ├── illum
  |   |   └── epoch_20_spa_0.05_exp_1.0.pth    
  |   |   
  |   ├── fusion_modelcolorv3_epoch_105.pth
  |        
```

After doing these, you can run all the notebook.
