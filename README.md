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

- [todo] 完成报告
- [ ] 检查邮件
- [x] 安排会议
                        

              
