## Trojan-Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/laogenihao/Trojan-Heroku)

开启运输插件作为入站隧道，侦听443端口即可...

## 食用方法

拷贝一份v2rayN客户端的本地config.json文件，修改下面的部分代码并粘贴到本地JSON文件的对应代码中，导入自定义节点即可...

  "outbounds": [


      "protocol": "trojan",


          {
            "address": "优选IP",
            "method": "chacha20",
            "ota": false,
            "password": "密码",
            "port": 443,
            "level": 1
          }
        ]
      },
      "streamSettings": {
        "network": "ws",
        "security": "tls",
        "tlsSettings": {
          "allowInsecure": false,
          "serverName": "反代地址.dev"
        },

    


          }
        }
      },

        "enabled": false,
        "concurrency": -1

    },





基于bclswl0827大佬的项目修改

原作者链接https
https://www.
