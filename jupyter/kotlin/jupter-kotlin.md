## 如何在jupyter里面使用kotlin
### 1、本地安装JDK8或更高版本
### 2、本地安装kotlin的内核
``` bash
git clone https://github.com/Kotlin/kotlin-jupyter.git

cd kotlin-jupyter

./gradlew installKernel

```
### 3、打开DataSpell， 打开settings
### 4、选择 "Python Interpreter" ，选择"System Interpreter" 选项， 然后选择刚刚安装好的kotlin内核的路径
### 5、点击 "OK" 确认关闭窗口
### 6、创建一个Jupyter notebook 时， 在右上角的内核选择下拉菜单中，可以看到并选择Kotlin内核，