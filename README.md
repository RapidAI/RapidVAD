## RapidVAD
<p align="left">
    <a href=""><img src="https://img.shields.io/badge/OS-Linux%2C%20Win%2C%20Mac-pink.svg"></a>
    <a href=""><img src="https://img.shields.io/badge/Python->=3.7,<=3.10-aff.svg"></a>
</p>


## TODO
- python版RapidVAD

#### 📖文档导航
- [Python](./python/README.md)

#### 🎨整体框架
```mermaid
flowchart LR

A([wav]) --RapidVAD--> B([各个小段的音频]) --RapidASR--> C([识别的文本内容]) --RapidPunc--> D([最终识别内容])
```

#### 📣更新日志
<details>
<summary>详情</summary>

- 2023-05-08 update:
    - Init

</details>
