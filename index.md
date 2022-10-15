# Welcome to Fahim's Dungeon

Bookmark this page to get updates on my upcoming projects.

## Projects

### Decentranet

Using IPFS and Blockchain to make a Decentralized Internet.

```markdown
Decentranet is a combination of three technologies. IPFS, Blockchain and Encryption. With Decentranet, 
we aim to secure data from wireless sensors by creating a network immune to attacks that exploit their 
single point of failure and from any other external threats. Any data uploaded on Decentranet will be 
encrypted and then distributed among all the nodes. This data will be identified by its cryptographic 
hash value. That means any modification or change made to the uploaded data will not go unnoticed. 
In this way we can make wireless sensor networks a much more reliable way of monitoring or collecting 
data. This project is beneficial for every industry that uses sensors or generates some data such as 
the military, industrial, agricultural, financial and even the medical sector.

[Solution_Model](https://drive.google.com/file/d/1bQxH2NFM2fNhgc6dAsyKPVCNOAEj7ocu/view?usp=sharing)
[Architectural_Model](https://drive.google.com/file/d/1Dh0heA0ERAGdRsReTPb0wW4jUTJcg7GH/view?usp=sharing)

**Genesis Block**
STEP 1
    Installing Required Packages
sudo apt-get install software-properties-common
sudo add-apt-repository -y ppa:ethereum/ethereum
sudo add-apt-repository -y ppa:ethereum/ethereum-dev
sudo apt-get update
sudo apt-get install ethereum

STEP 2
    On every node
geth --datadir node1 account new
STEP 3
    Use puppeth to create genesis file 
STEP 4
    Export the genesis file
STEP 5
    On every node
geth --datadir node1/ init genesis.json
```
### PyShark

A Python3 scapy based Packet Sniffer that has the capabilities of sniffing raw HTTP, TCP, UDP, ICMP, ARP packets and writing the output to .pcap for inspection within tools such as Wireshark.
```markdown
Features

    Python 3 Support
    Raw Packet Capturing
    Pure Python
    Cross-Platform
    Supported Layers: HTTP, TCP, UDP, ICMP

Installation:

Cloning:

    $ git clone https://github.com/pyshark/pyshark.git
    $ cd pyshark/
    $ pip3 install -r requirements.txt

First Run:

    $ python3 pyshark.py

Usage

    usage: pyshark.py [-h] [-c COUNT] [-f FILTER [FILTER ...]] [-H] [-o OUTFILE] [-i INTERFACE]

PyShark - HTTP Packet Sniffer.

    optional arguments:
      -h, --help            show this help message and exit
      -c COUNT, --count COUNT
                            Numbers of packets that you need to capture (0 = Infinity)
      -f FILTER [FILTER ...], --filter FILTER [FILTER ...]
                            The Berkeley Packet Filter (BPF) that you need to set. (Default is: 'port 80 and tcp') NOTE: You need to Specify them as a string
      -H, --http-only       Limit the results to display only http/https packets
      -o OUTFILE, --outfile OUTFILE
                            Store all the sniffed packet to a .pcap file (You don't need Specify the extension, just the file name.)
      -i INTERFACE, --interface INTERFACE
                            Specify an interface to sniff traffic on
```

## Support or Contact

[Github](https://github.com/fhmshehzad)

[Discord](https://drive.google.com/file/d/1OtPyWSYNsOFHaNZyMQOl2Fw77l3lrjyj/view?usp=sharing)

[Twitter](https://twitter.com/fhm_sh)

[LinkedIn](https://www.linkedin.com/in/fahim-shehzad/)
