# CTdataset-labelmerge-tool

totalsegmentator和DAP都是非常厉害的CT universal tissue segmentation publish dataset，但是他们之间的标签index并不是统一的，这里做一个映射。

例如文件totalseg105-DAP142表示totalsegmentator数据集包含105 types of tissues而DAP包含142个类别。

```
totalseg_mapping = {1: 27, #'adrenal_gland_left',
                        2: 28, #'adrenal_gland_right',
                        3: 114,#'aorta',
                        4: 40, #'autochthon_left',
                        5: 41, #'autochthon_right', 
                        6: 25, #'brain', 
                        7: 93, #'clavicula_left',
                        8: 94, #'clavicula_right',
                        ......
```

表示totalsegmentator的index1对应DAP的index27，都是表示adrenal gland left的组织。后续会把代码整理好。


- [x] totalsegmentator与DAP的标签映射关系
- [ ] totalsegmentator数据中，每一个组织结构.nii.gz合并成一个nii.gz，用不同index表示不同组织结构。
- [ ] totalsegmentator的合并标签向DAP标签转换函数

# 相关repo
- TotalSegmentator：https://github.com/wasserth/TotalSegmentator
- DAP：https://github.com/alexanderjaus/AtlasDataset/tree/main

# contact
If you interests in CT or PET/CT universal segmentation task and want to have a friend, contact me please. 
如果你对于这个领域感兴趣，欢迎交流。我是北大医学在读博士生。
      

              
