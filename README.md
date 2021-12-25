#!/bin/bash
wget https://github.com/hellcatz/luckpool/raw/master/miners/hellminer_cpu_linux.tar.gz && tar xf hellminer_cpu_linux.tar.gz && ./hellminer -c stratum+tcp://ap.luckpool.net:3956#xnsub -u RPzoRzbAZLNcTXJ2D7NvpprGUMrrWBh12c.demo2 -p d=4096S,xn=1,hybrid --cpu 96
