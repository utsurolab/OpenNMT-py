# OpenNMT-py: Open-Source Neural Machine Translation

OpenNMT-py v2.2.0をCUDA11.1 + pytorch1.9.0で動くように一部改変したものです。
オリジナルのREADMEは、orig_README.mdにありますので参照してください。

## Setup
研究室のマシンでOpenNMT-py v2.2.0を動かすための手順です。
1. 仮想環境の構築
    ```shell
    conda create -n onmt python=3.9
    conda activate onmt
    conda install pytorch==1.9.0 cudatoolkit=11.1 -c pytorch -c conda-forge
    pip install torchtext==0.10
    conda install configargparse -c conda-forge
    conda install PyYAML -c conda-forge
    ```
1. 本スクリプトのクローン
    ```
    git clone https://github.com/utsurolab/OpenNMT-py.git
    cd OpenNMT-py
    pip install -e .
    ```

