## YALMIP-SDPT3 安装流程

最新版地址：https://yalmip.github.io/download/

### 安装 YALMIP（ 5 Steps）
#### 1）删除现存旧版本 YALMIP
#### 2）clone（解压）YALMIP 到本地，解压后包含如下目录
* /yalmip
* /yalmip/@sdpvar
* /yalmip/extras
* /yalmip/demos
* /yalmip/solvers
* /yalmip/modules
* /yalmip/operators

#### 3) 在 MATLAB set path 中添加如下路径
* /yalmip
* /yalmip/extras
* /yalmip/demos
* /yalmip/solvers
* /yalmip/modules
* /yalmip/modules/parametric
* /yalmip/modules/moment
* /yalmip/modules/global
* /yalmip/modules/robust
* /yalmip/modules/sos
* /yalmip/operators

或者直接添加 YALMIP 和其所有子文件夹
#### 4) 重启 MATLAB	  
#### 5）测试是否安装成功：“which sdpvar”，如果显示相关路径表明安装成功     

### 安装 SDPT3 （ 4 Steps）
最新版地址：http://www.math.nus.edu.sg/~mattohkc/sdpt3.html

#### 1）clone（解压）SDPT3 到本地
#### 2）运行 MATLAB 并将当前目录切换至 SDPT3-4.0 目录下
#### 3）命令行 ”>>Installmex(1)"
如果 mex 出错，请自行 google 解决
#### 4）测试安装是否成功：“>>startup; sqlpdemo"
