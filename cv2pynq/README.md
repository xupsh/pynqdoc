# 通过PYNQ加速Opencv函数(cv2pynq)
## 如何配置PYNQ板卡以及安装cv2pynq库
### 关于配置PYNQ板卡的相关内容，请参考：
https://github.com/Xilinx/PYNQ
### 如何安装cv2pynq库
1. 在Jupyter界面中new选项里选择新建一个终端
2. 在PYNQ板卡能连接网络的情况下，在终端输入：
    ``` 
    sudo pip3 install --upgrade git+https://github.com/xupsh/cv2pynq.git
    ```
    安装成功后，在Jupyter的目录下会出现一个cv2PYNQ的文件夹，里面是对cv2pynq的简介
3. 如果PYNQ板卡无法连接网络，可以采取以下方法：<br>
    3.1  下载cv2pynq的zip压缩包<br>
    3.2  上传压缩包到PYNQ板卡<br>
    3.3  在终端中unzip上传的压缩包<br>
    3.4 移动到解压的目录下然后采用pip安装
```
sudo pip3 install -e .
```
