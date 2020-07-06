# Spine-Unity UPM Project

### 介绍
Spine Unity运行时的UPM兼容项目

### 版本说明
1. Spine运行库版本：3.8.0
2. 所需Unity版本：2019.x

### 导入方法

#### 一、Package Manager
1. 打开Package Manager
2. 点击左上角+号，选择Add package from git URL
3. 输入https://gitee.com/leesinlcj/spine-unity.git
4. 点击add即可导入

#### 二、直接修改manifest.json文件
1. 打开项目根目录/Packages文件夹下的manifest.json文件
2. 在dependencies下添加一行 "com.esotericsoftware.spine.spine-unity": "https://gitee.com/leesinlcj/spine-unity.git",
3. 导入完成