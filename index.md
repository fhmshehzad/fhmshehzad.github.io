# Welcome to Fahim's Dungeon

Bookmark this page to get updates on my upcoming projects.

## Projects

### DecentraX

Using IPFS and Blockchain to make a Decentralized Internet.

```markdown
DecentraX is a combination of three technologies i.e. IPFS, blockchain and encryption. Data is encrypted and uploaded on the IPFS network where it is identified by its cryptographic hash. This hash value is then stored on a blockchain so it can't be modified or deleted. In case of any unauthorized access or alteration of the content from other nodes, a new hash value is created which signals that the integrity of data is no longer preserved. Moreover, objects on the IPFS network are replicated automatically. If some gateway nodes stop working due to errors or network attacks, users can access the other nodes. Contents are delivered from the closest peers that possess a copy of the contents thus making sure that the data is available at all times. An architecture diagram of DecentraX is given below.

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
```markdown

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
