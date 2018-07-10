# FaceTests
sudo apt-get update
   35  nvcc --version
   36  sudo apt install nvidia-cuda-toolkit
   37  --fix-missing
   38  sudo apt-get update
   39  sudo apt-get --fix-missing
   40  sudo apt install nvidia-cuda-toolkit
   41  nvcc --version
   42  sudo apt-get install cuda-command-line-tools
   43  sudo apt-get update
   44  sudo dpkg -i cuda-repo-ubuntu1604_9.0.176-1_amd64.deb
   45  sudo dpkg -i cuda-repo-ubuntu1604-9-0-local_9.0.176-1_amd64.deb 
   46  sudo apt-key add /var/cuda-repo-9-0-local/7fa2af80.pub
   47  sudo dpkg -i cuda-repo-ubuntu1604-9-0-local_9.0.176-1_amd64.deb 
   48  sudo dpkg -i cuda-repo-ubuntu1604-9-0-local-cublas-performance-update_1.0-1_a
   49  sudo dpkg -i cuda-repo-ubuntu1604-9-0-local-cublas-performance-update-2_1.0-1_amd64.deb 
   50  sudo dpkg -i cuda-repo-ubuntu1604-9-0-local-cublas-performance-update-3_1.0-1_amd64.deb 
   51  sudo dpkg -i libcudnn7_7.0.5.15-1+cuda9.0_amd64.deb 
   52  sudo dpkg -i libcudnn7-dev_7.0.5.15-1+cuda9.0_amd64.deb 
   53  sudo dpkg -i libnccl2_2.1.4-1+cuda9.0_amd64.deb 
   54  sudo dpkg -i libnccl-dev_2.1.4-1+cuda9.0_amd64.deb 
   55  sudo apt-get update
   56  sudo apt-get install cuda
   57  sudo apt-get install libcudnn7-dev
   58  sudo apt-get install libnccl-dev
   59  gcc
   60  gcc --version
   61  lspci | grep -i nvidia
   62  uname -m && cat /etc/*release
   63  uname -r
   64  sudo apt-get install linux-headers-$(uname -r)
   65  cudda version
   66  cudd version
   67  nvcc --version
   68  sudo apt-get purge cuda
   69  sudo apt-get purge libcudnn6
   70  sudo apt-get purge libcudnn6-dev
   71  nvcc --version
