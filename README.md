## Manim社区中的Examples

这里仅保存一下从[Manim社区](https://docs.manim.community/en/stable/examples.html)中复制下来的示例（基于[v0.18.1版本](https://hub.docker.com/r/manimcommunity/manim/tags)），方便本地查阅/调试。

### 本机安装[ffmpeg](https://ffmpeg.org/download.html)
运行Manim前需要安装一下[ffmpeg](https://ffmpeg.org/download.html)，并将`ffmpeg`配置到系统的环境变量中。

### 本地运行

- 用docker运行Manim容器
    
    > Tip: 如果是在windows系统运行，应将`\`替换为`
    ```shell
    docker run -it -d \
    --name manim \
    -p 8888:8888 \
    -v ~/notebooks/manim:/manim \
    manimcommunity/manim:v0.18.1 \
    jupyter lab --ip=0.0.0.0
    ```

- 打开jupyter页面：[http://127.0.0.1:8888](http://127.0.0.1:8888)

- 克隆本仓库或直接复制`examples.ipynb`到`jupyter`的目录下：
    ```shell
    cd ~/notebooks/manim

    git clone https://github.com/Samge0/manim-examples.git
    ```

- 在`jupyter`运行/调试示例即可


### 生成的示例视频

