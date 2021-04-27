# d2l_learning

动手深度学习，练习

#### macbook M1 安装指南：

* 安装M1版本的 conda， conda-forge:
    * https://github.com/conda-forge/miniforge/#download
    * 使用 homebrew `brew install miniforge`


* 配置 conda 镜像点
     ```shell
        conda config --add channels https://mirrors.ustc.edu.cn/anaconda/pkgs/main/
        conda config --set show_channel_urls yes
        conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/conda-forge/
        conda config --show
     ```

* 新建conda环境，
    * https://zh-v2.d2l.ai/chapter_installation/index.html


* 在idea 中,配置conda中的python解释器
    * https://www.jb51.net/article/187721.htm


* 安装相关的依赖包
    ```shell
    conda activate d2l
    conda install pytorch torchvision -c pytorch '-c=conda-forge'
    pip install -U d2l
    jupyter notebook
    ```