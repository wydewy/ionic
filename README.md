# ionic

#环境搭建

##安装node.js

###卸载旧版本node.js

    sudo apt-get remove nodejs npm -y 

    cd /usr/local/src/
    sudo wget http://nodejs.org/dist/v7.2.0/node-v7.2.0.tar.gz
    sudo tar zxvf node-v7.2.0.tar.gz
    cd node-v7.2.0/
    sudo  ./configure
    sudo make
    sudo make install
    cd ~
    node -v
    npm -v
    
##安装cordova和ionic

        sudo npm install -g cnpm --registry=https://registry.npm.taobao.org
        sudo cnpm install -g cordova ionic 

###测试

        cordova -v
        ionic -v
        
        ionic start MyIonic2Project tutorial --v2
        
        sudo ionic start --v2 myApp tabs
