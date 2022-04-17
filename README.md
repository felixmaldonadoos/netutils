# Background
Personal repo with helpful network/data diagnostic scripts I developed to test network connectivity, data transfer, etc. Work in progress, will be adding more as I continue my research projects. 

I started this repo with the final goal of compiling useful diagnostic scripts to check TCP (currently only one) network status. I plan on implementing the following tools soon: 
- Lab Streaming Layer (LSL)
- Serial

# connect2tcp.py

Reads in a TCP/IP address and port from ```testaddress.txt``` and tries to connect to it and prints 
out latency values in ms. Default IP address is ```localhost: 127.0.0.1 ``` and ```port:5678```. By default this script will try
to connect to network 3 times (change this with ```RUNS``` variable. 

