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



https://github.com/user-attachments/assets/02b39f5f-78e7-450e-98a8-30f0e93e964d



https://github.com/user-attachments/assets/8d5fb791-1db2-43cb-ae61-4e6c60eb59cd



https://github.com/user-attachments/assets/e3daa604-d637-421e-bc72-b9e0176b3e6e



https://github.com/user-attachments/assets/5304d827-9e12-4c11-9faf-66fc50a72b0c



https://github.com/user-attachments/assets/39b44ab1-63dc-4f3d-ac0b-c29a7c7c94d1



https://github.com/user-attachments/assets/9bb74205-de45-440a-b879-7c18a3301e1a



https://github.com/user-attachments/assets/f76f1dfc-62ea-4c19-87f6-7cac28f71f67



https://github.com/user-attachments/assets/621b1bfc-c1b1-4384-b8ca-0cf815d0f39f



https://github.com/user-attachments/assets/05da23cf-8281-4c2b-81a5-8505e01aecd7



https://github.com/user-attachments/assets/6b7495a3-97e7-4a68-b060-30fe55b1e4dd



https://github.com/user-attachments/assets/8ebbd753-cbef-4bcc-9099-2197d9d581d1



https://github.com/user-attachments/assets/b388c6f8-48b6-4983-9271-74cd9e95d85e



https://github.com/user-attachments/assets/fc6ef925-f368-409b-8fd0-7c2d449d175b



https://github.com/user-attachments/assets/7d51a74a-208b-486c-89b2-27ed2eeaa17c



https://github.com/user-attachments/assets/b93815cf-9978-4a60-af3a-880ce3922643



https://github.com/user-attachments/assets/2d72d82c-4bcc-4583-b74d-1067818eee24



https://github.com/user-attachments/assets/d67f5426-68ae-4b5b-96f1-55289957b7ad



https://github.com/user-attachments/assets/d8fe051b-4903-4ca2-a6eb-b2febbd33af4



https://github.com/user-attachments/assets/28c1ea6a-3d0c-46e4-a63b-9324d942bdd3



https://github.com/user-attachments/assets/3e258287-e2e9-4b15-abb8-372e8a3d3173



https://github.com/user-attachments/assets/0a0154df-94ba-45c4-8b78-2cddff50676c


