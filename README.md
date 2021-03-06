<img align="right" width="135" height="135"
     title="PTTBot logo" src="./images/pttbot_icon.png">
# PTTBot ![PTTBot](https://img.shields.io/badge/PTT-Chatbot-red.svg)


>The PTTBot is the course project of Intelligent Conversational Bot (2017 ICB)  and win the prize awarded by EmotiBot.

[![PTTBot](https://img.shields.io/badge/Course-2017_ICB-brightgreen.svg)](https://www.csie.ntu.edu.tw/~yvchen/s105-icb/) ![Reward](https://img.shields.io/badge/Reward-EMOTIBOT-blue.svg)

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

* [Prerequisites](#prerequisites)
* [Usage](#usage)



## Prerequisites

### Download
Please download packages by executing download.sh before running the code:
```bash
$ bash download.sh
```

### Python Requirements
The python version is Python 2.7.
The required library is listed below .
```bash
Flask==0.12.2
gym==0.10.5
h5py==2.7.1
keras-rl
tensorflow==1.0.0
keras>=2.0.2
h5py>=2.6.0
pandas>=0.13.1
apiai
```
(Recommend) Automatically Install by one command .
```bash
$ cd PTTBOT_DEMO
$ pip install -r requirements.txt
```

### Config
Change Keras configuration.
`image_data_format` and `backend` in `~/.keras/keras.json`
```
{
    "epsilon": 1e-07,
    "floatx": "float32",
    "image_data_format": "channels_last",
    "backend": "theano"
}
```



## Usage
### Run the server
```bash
$ python server.py
```

### Web Interface
To test the chatbot, open the browser and type in http://localhost:5000 [link](http://localhost:5000)


## Authors

| [<img src="https://avatars3.githubusercontent.com/u/17563176?s=460&v=4" width="125px;"/><br /><sub><b>Chung Kai Hsieh</b></sub>](https://github.com/account)<br />        | [<img src="https://avatars0.githubusercontent.com/u/22479778?s=460&v=4" width="125px;"/><br /><sub><b>HungWei-Andy</b></sub>](https://github.com/HungWei-Andy)<br />  | [<img src="https://avatars0.githubusercontent.com/u/24911155?s=460&v=4" width="125px;"/><br /><sub><b>ChaohuiYu</b></sub>](https://github.com/ChaohuiYu)<br />          | [<img src="https://scontent.fkhh1-2.fna.fbcdn.net/v/t1.0-9/600984_382974335099334_1394295018_n.jpg?_nc_cat=0&_nc_eui2=v1%3AAeFtsIiDXhJctKU_uHiLGHyxIPQwqTW05v5zzQgkbXJXMSXwXKB8whndBJlFUGyy10L5KVE2QyTA6-CZWt0t4LRGrYRoIo2EskGN2jvTm8oEjg&oh=4a3114031fe396334dd22e3c2ee70839&oe=5B68F9E9" width="125px;"/><br /><sub><b>Zheng Pei Chun</b></sub>](https://www.facebook.com/rubbincheng?ref=br_rs)<br /> |
|:---:|:---:|:---:|:---:|
## Reward
2017 Chatbot Competition : Emotibot Reward

| <img src="./images/reward_people.png" alt="Reward picture" width="275" height="220"> | <img src="./images/certificate.png" alt="Certificate" width="275" height="220"> |
|:---:|:---:|





