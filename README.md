---
title: Table_Transformer
emoji: 🚀
colorFrom: white
colorTo: red
sdk: streamlit
sdk_version: 1.10.0
app_file: app.py
pinned: false
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference


###Run TDTSR Script

python tdtsr.py location padd_top left right bottom table detection threshold table structure recginition threshold
```commandline
python tdtsr.py "C:/Users/Gowtham/Desktop/Work/Workbench/Projects/Table Transformer  - Salml/Table Images/Img_4_Structured_Multiple_Tables.png" 30 30 30 30 0.6 0.8
```
No Padding values( Default = 20 )
```commandline
python tdtsr.py "C:/Users/Gowtham/Desktop/Work/Workbench/Projects/Table Transformer  - Salml/Table Images/Img_4_Structured_Multiple_Tables.png" 
```
