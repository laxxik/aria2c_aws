Compilled statement

%cd "~/sagemaker-studiolab-notebooks/tmp"
!wget "https://github.com/aria2/aria2/releases/download/release-1.36.0/aria2-1.36.0.tar.gz"
!tar -xvzf "aria2-1.36.0.tar.gz"
%cd "aria2-1.36.0"
!./configure
!make

Use pattern
wget "https://github.com/laxxik/aria2c_aws/archive/refs/heads/main.zip"
!unzip main.zip
%cd aria2c_aws-main
!chmod 755 aria2c
!./aria2c <options>
