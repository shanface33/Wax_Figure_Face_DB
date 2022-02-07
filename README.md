# Wax Figure Face Database (WFFD) for face spoofing [<a href="https://arxiv.org/pdf/1906.11900.pdf?ref=https://githubhelp.com">Paper</a>]

The Wax Figure Face Database (WFFD) verison 1 was proposed in our ICIAP2019 paper (Jia, S. et al., ICIAP2019), which includes wax figure faces as super-realistic 3D presentation attacks. It consists of 2200 images with both real and wax figure faces (totally 4400 faces) with a high diversity from online collections. For more details please refer to our paper:
Jia, Shan, et al. "A database for face presentation attack using wax figure faces." International Conference on Image Analysis and Processing. Springer, Cham, 2019.

---------------------------------------------------
The database contains three folders "ProtocolX" (Protocol ID) with images in three subfolders:
* Protocol1: the wax figure face  and real faces image pairs came from different recording devices and environment, and were grouped manually;
#image: /Train (600), /Dev (200); /Test (200); total: 1000
* Protocol2: the wax figure face  and real face pairs were recorded in the same environment with the same cameras;
#image: /Train (720), /Dev (240); /Test (240); total: 1200
* Protocol3: previous two protocols are combined to simulate the real-world operational conditions;
#image: /Train (1320), /Dev (440); /Test (440); total: 2200

---------------------------------------------------
The WFFD database is released only for academic researches. Any researchers from educational institute are allowed to use this database freely for noncommercial purpose.

---------------------------------------------------
If you use this database, please cite the following publication:
```
@inproceedings{jia2019database,
  title={A database for face presentation attack using wax figure faces},
  author={Jia, Shan and Hu, Chuanbo and Guo, Guodong and Xu, Zhengquan},
  booktitle={International Conference on Image Analysis and Processing},
  pages={39--47},
  year={2019},
  organization={Springer}
}

