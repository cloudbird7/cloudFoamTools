 ----------------------------------------------------------------------------
                  ____    ___                       __     
                 /\  _`\ /\_ \                     /\ \    
                 \ \ \/\_\//\ \     ___   __  __   \_\ \   
                  \ \ \/_/_\ \ \   / __`\/\ \/\ \  /'_` \  
                   \ \ \L\ \\_\ \_/\ \L\ \ \ \_\ \/\ \L\ \ 
                    \ \____//\____\ \____/\ \____/\ \___,_\
                     \/___/ \/____/\/___/  \/___/  \/__,_ /
 
                              CloudBird‘s CodeLib
 
        Name: cloudFoamTools       Version: 1.3.1       UpdateDate:     20200617     
 
        Description:
        cloudFoamTools provides some useful programs for openfoamer:
 
        *toolsList:*
        Allsimu: perform a series of simulations in order
        foamDictX: check or set the case's configuration with a AllDictList file
        foamAllDictX:set the  configuration for a series of cases with a AllDictList file
        foamGetX:get the scripts to run postProcess tools like probes and singelGraph for a series of cases
        (Tips: you can use the OpenFOAM local tool “foamGet”to get our tools, e.g. foamGet foamDictX)        
 
        Writer:       CloudBird         cloudbird7@foxmail.com
 ------------------------------------------------------------------------------
## Introduction
"cloudFoamTools" is a series of Linux shell scripts designed for OpenFOAM. At present, the scripts are very humble and user documents still needs time to beimproved. At this stage, you can get the usage  by the header information at the beginning of each script. The "- help" option is also avaliable for most scripts.
## Install and uninstall
You can install cloudFoamTools with the 'Install' scripts in the Install folder:
```sh
./Install -i
```
Change the option to `- r`  to uninstall cloudFoamTools.
## 简介
"cloudFoamTools" 是一个为OpenFOAM设计的一系列linux shell脚本该脚本目前处于起步阶段，相关文档暂时没有编写，功能也比较单一，后续将进行相应补充。在目前阶段，你可以通过每个脚本开头的头文件信息来获得相应脚本的用法，对脚本附加 -help选项也可以获得更多信息。
## 安装与卸载
解压Install.tar.xz，进入Install文件夹，在终端运行：
```sh
./Install -i
```
将参数改为`-r` 可以进行卸载