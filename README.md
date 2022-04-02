# OpenNMT-py: Open-Source Neural Machine Translation

オリジナルのREADMEは、orig_README.mdにありますので参照してください。

## Setup
研究室のマシンでOpenNMT-py 2.2.0を動かすための手順です。
1. 仮想環境の構築
    ```shell
    conda create -n onmt python=3.9
    conda activate onmt
    conda install pytorch==1.9.0 cudatoolkit=11.1 -c pytorch -c conda-forge
    ```
1. 本スクリプトのクローン
    ```
    git clone https://github.com/utsurolab/OpenNMT-py.git
    cd OpenNMT-py
    pip install -e .
    ```

