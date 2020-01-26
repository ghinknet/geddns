#### Compliance with LGPLv3 protocol
#### Help Document:[https://www.alibabacloud.com/help](https://www.alibabacloud.com/help)
#### Website:[https://www.ghink.net](https://www.ghink.net)
#### Gitee:gitee.com/ghink
#### Donate:afdian.net/@ghink

## About JSON File:

#### {
####     "RR": "",
####     "Domain": "",
####     "IPV4": "",
####     "IPV6": "",
####     "accessKeyId": "",
####     "accessSecret": ""
#### }

#### RR:Your RR
#### Domain:Your Main Domain
#### IPV4:IPV4 DDNS On(true)/Off(false)
#### IPV6:IPV6 DDNS On(true)/Off(false)
#### accessKeyId:Your AliDNS accessKeyId
#### accessSecret:Your AliDNS accessSecret

### Example
#### Your DDNS Domain is:test.example.com
#### You Want to use IPV4,But Do Not Want To Use IPV6 DDNS

#### {
####     "RR": "test",
####     "Domain": "example.com",
####     "IPV4": "true",
####     "IPV6": "false",
####     "accessKeyId": "example",
####     "accessSecret": "example"
#### }

### More Help:https://www.alibabacloud.com/help

# About Language/Enviroment

### Core Code is Python
#### Python Use These Extend（Need To Install)：
#### requests
#### aliyun-python-sdk-core
#### aliyun-python-sdk-alidns

### Install Command(pip):
#### pip install requests
#### pip install aliyun-python-sdk-core
#### pip install aliyun-python-sdk-alidns


