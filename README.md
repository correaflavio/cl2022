# Cisco Live 2022 Workshops

Welcome to my Cisco Live 2022 DevNet Workshops. Here you have quick instructions about how to get access to it, install the requirements and start working on it via jupyter notebooks. Enjoy!

#### 1) Access the DevNet Lab environment based in the DevNet Workshop that you are:

DEVWKS-1391 - Building your first ML model using your network WiFi data
https://testing-developer.cisco.com/learning/labs/devwks-1391/introduction/ 

or

DEVWKS-2150 - Predicting your office occupancy and environmental status using Machine Learning
https://testing-developer.cisco.com/learning/labs/devwks-2150/

<br>

#### 2) Log with your DevNet preferred credential

<br>

#### 3) Click Start Learning to get access to the lab environment

<br>

#### 4) Using the terminal, clone this repo at your lab environment.

**developer:src>** git clone https://github.com/correaflavio/cl2022

<br>

#### 4) Enter at the directory of your lab

**developer:src>** cd cl2022/devwks_1391 

or

**developer:src>** cd cl2022/devwks_2150 

<br>

#### 5) Install the packages required

**developer:src>** pip3 install -r requirements.txt

<br>

#### 6) Install graphviz app at the terminal using apt-get

**developer:src>** sudo apt-get install graphviz

<br>

#### 7) Start the jupyter notebook

**developer:src>** jupyter notebook

<br>

#### 8) Copy the token created during the execution

<br>

#### 9) Run Caddy webserver in another terminal window

**developer:src>** caddy run

<br>

#### 10) On the top blue bar of the DevNet lab, click on the briefcase icon to get the Caddy web server URL. Click to open it in your default browser. It will be a URL like "app-8080-long-ID.devenv-int.ap-ne-1.devnetcloud.com".
