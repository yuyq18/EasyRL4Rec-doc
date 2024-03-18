## Installation

1. Clone this git repository and change directory to this repository:

   ```shell
   git clone https://github.com/chongminggao/EasyRL4Rec.git
   cd EasyRL4Rec/
   ```

2. A new [conda environment](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/environments.html) is suggested. 

   ```bash
   conda create --name easyrl4rec python=3.11 -y
   ```

3. Activate the newly created environment.

   ```bash
   conda activate easyrl4rec
   ```

4. Install the required modules from pip.

   ```bash
   sh install.sh
   ```

   Install the tianshou package from my forked version:

   ```bash
   cd src
   git clone https://github.com/yuyq18/tianshou.git
   cd ..
   ```

## Download the data

1. Download the compressed dataset

   ```bash 
   wget https://nas.chongminggao.top:4430/easyrl4rec/data.tar.gz
   ```

   or you can manually download it from this website:
   https://rec.ustc.edu.cn/share/a3bdc320-d48e-11ee-8c50-4b1c32c31e9c


2. Uncompress the downloaded `data.tar.gz`. The following command will directly extract `data.tar.gz` into the `.data/` directory and merge it with the existing files under `.data/`.

   ```bash
   tar -zxvf data.tar.gz
   ```

   Please note that the decompressed file size is as high as 8.1GB. This is due to the large space occupied by the ground-truth of the user-item interaction matrix. 

   

If things go well, you can run the following examples now！Or you can just reproduce the results in the paper.
