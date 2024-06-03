# UnrealCV

Forked from [UnrealCV](https://github.com/unrealcv/unrealcv), for Unreal Engine 5.3.

## Prerequisites

- [Unreal Engine 5.3](https://www.unrealengine.com/)

- [MS Visual Studio 2022](https://dev.epicgames.com/documentation/en-us/unreal-engine/setting-up-visual-studio-development-environment-for-cplusplus-projects-in-unreal-engine?application_version=5.3)

- Python 3.12

## Build UnrealCV Plugin

```bash
$ git clone git@github.com:xuchenhao001/unrealcv.git
$ cd unrealcv/
# https://docs.unrealcv.org/en/master/plugin/install.html
$ pip install -U unrealcv
$ python build.py --UE4 "C:\Program Files\Epic Games\UE_5.3"
# the plugin binaries will be produced in the Plugins/UnrealCV folder. 
# Then you can copy the compiled plugin to Plugins folder.
```

## Citation

If you found this project useful, please consider citing our paper

```bibtex
@article{qiu2017unrealcv,
  Author = {Weichao Qiu, Fangwei Zhong, Yi Zhang, Siyuan Qiao,Zihao Xiao, Tae Soo Kim, Yizhou Wang, Alan Yuille},
  Journal = {ACM Multimedia Open Source Software Competition},
  Title = {UnrealCV: Virtual Worlds for Computer Vision},
  Year = {2017}
}
```

## Contact

If you have any suggestion or interested in using UnrealCV, please [contact us](http://unrealcv.github.io/contact.html).
