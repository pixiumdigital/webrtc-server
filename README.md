# react-native-webrtc-server
The signaling server for https://github.com/oney/react-native-webrtc
You can checkout this demo https://github.com/oney/RCTWebRTCDemo
Demo server: https://react-native-webrtc.herokuapp.com/

# Deploy on Ec2

```sh
sudo su
cd /opt
curl --silent --location https://rpm.nodesource.com/setup_10.x | sudo bash -
yum -y install nodejs
yum install git
git clone https://github.com/pixiumdigital/webrtc-server.git
cd webrtc-server
npm install
npm audit fix
npm install forever -g
forever start app.js
```

# Get started

1. `npm install`
2. `npm start`
