## Install XMRig on Raspberry Pi

> For other devices, Install XMRig [here](https://github.com/NajmAjmal/xmrig-install)

# Method 1: Install direct from the source


    sudo apt update && sudo apy upgrade -y
    sudo apt full-upgrade -y
    sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y
    git clone https://github.com/xmrig/xmrig.git
    cd xmrig
    mkdir build
    cd build
    cmake ..
    make
    cd
    ./xmrig/build/xmrig -o gulf.moneroocean.stream:80 -u 4657q4dnsjLWtzeW4XN3wG9swFumWAZB9i1pegTLMxVAQy5E5AE8uif42kkHWcWc9vDcLUmzeCf3pV7mmrJQQqqe84dtASi -p Raspberry-Pi
  
  
For the last command you can customise it to your on preference by changing the,

<ul>
  <li>Pool name: -o</li>
  <li>Miner address: -u</li>
  <li>Miner name: -p</li>
</ul>

# Method 2 (Quick install)

If you are going to use Moneroocean As your Mining pool, Then you can use this to quickly install scripts on ANY Linux computer


    sudo wget -qO- https://raw.githubusercontent.com/ameila12322/xmrig-install-raspberrypi/main/install | bash
    

View your mining progress at [Moneroocean.stream](https://moneroocean.stream/)


#  Donate
    
    
This code is **100% free** to use, and we would greatly appreciate any donations to help support our work. If you'd like to donate, you can use the following cryptocurrency addresses:


    BTC:  33qQZT1F5mWPvqM2bjbxQ3AsSYMXHpJsr6
    
    ETH:  0x641E1449c2f7883F245069f284fC880174b02094
    
    SOL:  AeYJTfLnok1nkncnvXFoKXmH8zrvtB7heNL9Q2sKNaFr
    
    XMR:  4657q4dnsjLWtzeW4XN3wG9swFumWAZB9i1pegTLMxVAQy5E5AE8uif42kkHWcWc9vDcLUmzeCf3pV7mmrJQQqqe84dtASi


Thank you for choosing our Xmrig install on Raspberry Pi Commands. We hope you find it useful and profitable

