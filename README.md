# Introduction
This is the code for paper "Unsupervised Deep Cross-Language Entity Alignment", which provides an unsupervised entity alignment method.

# Runtime Dependencies
* lap
* numpy
* urllib
* requests
* sentence_transformers
 

# Dataset
Please download the public DBP15K dataset from "https://drive.google.com/file/d/1Now8iTn37QYMOUC80swlBq9QKxKhFmSU/view?usp=share_link" and place three cross-language datasets under the directory of "datasets".


# Running
Please run the file "udcea.py" directly.


# Directory Structure  
-code  
 　-udcea.py  
-datasets  
 　-zh_en  
 　 　-zh_att_triples  
 　 　-zh_rel_triples  
 　 　-ent_ILLs  
 　 　-en_att_triples  
 　 　-en_rel_triples  
 　-ja_en  
 　-fr_en  
-multi-view information  
 　-zh_en  
 　 　-zh_att_tar  
 　 　-zh_att_rel  
 　 　-zh_str_tar  
 　 　-en_att_tar  
 　 　-en_att_rel  
 　 　-en_str_tar  
 　-ja_en  
 　-fr_en  
-translate files  
 　-zh_en  
 　 　-zh_align_trans  
 　 　-zh_att_tar_trans  
 　 　-zh_att_rel_trans  
 　 　-zh_str_tar_trans  
 　-ja_en  
 　-fr_en  

```
@inproceedings{udcea,  
 　 　author = {Chuanyu Jiang and  
 　 　 　 　 　  Yiming Qian and  
 　 　 　 　 　  Lijun Chen and  
 　 　 　 　 　  Yang Gu and  
 　 　 　 　 　  Xia Xie},  
 　 　title = {Unsupervised Deep Cross-Language Entity Alignment},  
 　 　booktitle = {Machine Learning and Knowledge Discovery in Databases: Research Track
                  - European Conference, {ECML} {PKDD} 2023, Turin,  
 　 　 　 　 　 　Italy, September 18-22, 2023, Proceedings, Part {IV}},  
 　 　series = {Lecture Notes in Computer Science},  
 　 　volume = {14172},  
 　 　pages = {3--19},  
 　 　publisher = {Springer},  
 　 　year = {2023}  
}
```