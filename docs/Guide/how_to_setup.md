
**1. Setup a MasterNode**

**Prerequisite**

 1. Operating System : Ubuntu 16.04 64-bit or higher Should be facing internet directly with public IP & without NAT

 2. Tools: Git, Docker, Docker Compose

 3. Network Ports

Following network ports need to be open for the nodes to communicate.

8545  TCP - RPC <br>   
30303 TCP/UDP - XDC

**How to Setup Masternode ?**

**0. Install Git**

* Check whether git is preinstalled.

    > git --version

If present, output will be something like git version 2.17.1. in this case, go to step a.

* Otherwise follow the below steps.

    1. sudo apt update
    2. sudo apt install git
    3. git --version

* Configure Git.

    1. git config --global user.name "Your Name"
    2. git config --global user.email "youremail@domain.com"

**a. Clone repository**

Run the following commands on your terminal.

    1. git clone [https://github.com/XinFinOrg/XinFin-Node.git](https://github.com/XinFinOrg/XinFin-Node.git)
    2. cd XinFin-Node

The git clone command will create a new folder XinFin-Node. cd XinFin-Node command changes the current directory to XinFin-Node

**b. Install docker & docker-compose**

       sudo ./install\_docker.sh

The above command will install docker and docker-compose for you.

**c. Update .env file with details**

* Copy a env.example file from XinFin-Node directory and name it as a .en
* Open .env file and edit values for following

     1. INSTANCE_NAME : A Display name of your masternode
     2. CONTACT_DETAILS : Your Email ID

![overview](/assets/xinfin-node.png)

![overview](/assets/masternode-.env.png)


**d. Start your Node**

        sudo docker-compose -f docker-services.yml up -d

This will start a Masternode and connect to a XinFin Testnet.

You should be able to see your node listed on this page: [XinFin Network](https://www.xinfin.network) (Make sure, you are connected to XinFin Testnet. If not, switch to Tesnet on top right corner)

Your coinbase address can be found in xdcchain/coinbase.txt file.

![overview](/assets/masternode-listing.png)

**2. Stake XDC**

  **Create XDC Wallet**

      > Visit http://xinfin.network/#webWallet and Click on create a new wallet.
      > you can create use a web wallet or download eWallet app from Google Play Store.
      > Create an account
      > Store your private key at a safe place (Hardware wallet is recommended)

![overview](/assets/xinfin_wallet.png)


   **Buy XDC**

     > get your free XDC to use on XinFin Testnet
     > Visit XinFin TestNet Faucet http://xinfin.network/#getTestXDC.
     > Add your wallet address created in step 2.b and request XDC

![overview](/assets/masternode-faucet.png)

   **Upload Kyc**

    > Visit http://xinfin.network/#masternode
    > Upload a notarized kyc



# **Kramaa Navigate Document**

- Kramaa is a Singapore based technology company converging latest technologies in blockchain, IoT, and analytics. The Company has created a blockchain based application ("The platform") for IoT identities linked to physical assets on Xinfin's proven hybrid blockchain architecture. 

- The platform securely integrates physical assets & IoT devices through blockchain, smart contracts & firmware for creating digital identity, provenance, authentication, e-commerce, supply chain & finance. Industry applications for the platform include smart cities, pharma, packaging, logistics, Fashion / Luxury, Food & beverages, precious metals &Jewelry.

- Kramaa will also offer an open API to build applications leveraging the registry platform

- Industry - Pharmaceuticals, Smart City, Art and Collectibles, Fashion and Luxury, Food & Beverages, Logistics

- Use Cases - Digital Identity, Authentication, Track and Trace, Anti- Counterfeit, Tokenization and Automation

- This document will give a brief overview on Kramaa and how to navigate the platform step by step


**Kramaa Architecture**

![Architecture](/assets/1.jpg)


**Brief summary of the platform**

![Summary](/assets/2.jpg)

How to access the platform ?

There are two ways to access / login the platform. 

- Accessing it from the website www.kramaa.com and then clicking on the Login button will take you to login page

![Summary](/assets/3.jpg)


- The second way is accessing it directly by entering https://demo.kramaa.comin the URL address bar of your browser

![Summary](/assets/4.jpg)

The platform works on all major web browsers and can also be accessed from your smartphone

![Summary](/assets/5.jpg)

![Summary](/assets/6.jpg)

![Summary](/assets/7.jpg)

![Summary](/assets/8.jpg)

![Summary](/assets/9.jpg)

![Summary](/assets/10.jpg)

![Summary](/assets/11.jpg)

![Summary](/assets/12.jpg)

![Summary](/assets/13.jpg)

![Summary](/assets/14.jpg)

![Summary](/assets/15.jpg)

![Summary](/assets/16.jpg)

![Summary](/assets/17.jpg)

![Summary](/assets/18.jpg)

![Summary](/assets/19.jpg)

![Summary](/assets/20.jpg)

![Summary](/assets/21.jpg)


Once a device is assigned we can view various analytics on the thing based on the information received from the device Track & Trace Function - Capturing location & temperature information on the platform using a sensor  


![Summary](/assets/22.jpg)

Capturing location information on the platform using a sensor  

![Summary](/assets/23.jpg)

If you click on setting there will be an option to invite other colleagues from your organization

![Summary](/assets/24.jpg)
