<b>Statement used for compilation</b><br/>
<br/>
%cd "~/sagemaker-studiolab-notebooks/tmp"<br/>
!wget "https://github.com/aria2/aria2/releases/download/release-1.36.0/aria2-1.36.0.tar.gz"<br/>
!tar -xvzf "aria2-1.36.0.tar.gz"<br/>
%cd "aria2-1.36.0"<br/>
!./configure<br/>
!make<br/>
<br/>
<b>Use pattern</b><br/>
<br/>
wget "https://github.com/laxxik/aria2c_aws/archive/refs/heads/main.zip"<br/>
!unzip main.zip<br/>
%cd aria2c_aws-main<br/>
!chmod 755 aria2c<br/>
!./aria2c <options><br/>
