# 使用方法

git clone https://github.com/lemonhall/paho.mqtt.wxapp.git

执行mvn后会在target下生成paho-mqtt.js、paho-mqtt.min.js，然后在微信小程序里引入即可

# 通过npm安装

npm install --save paho.mqtt.wxapp

sample目录是我写的一个小程序连接MQTT broker的demo

# 针对微信域名限制的修改

作者：lemonhall
针对：https://github.com/tennessine/paho.mqtt.wxapp.git

做了新的修改，微信小程序对域名后的:80和:443是会做拦截的

所以注释掉了对应的port部分
