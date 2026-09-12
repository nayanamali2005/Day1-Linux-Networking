
# Day 1 - Linux Networking & AWS EC2 Practical

This repository contains my Day 1 practical tasks completed using **Amazon Linux 2023 on AWS EC2**.

## Topics Covered

- Linux IP Investigation
- IPv4 Address Analysis
- Dynamic IP Investigation
- AWS EC2 Linux Server & IP
- Cloud Network Troubleshooting
- Nginx Service Verification

## Environment

- AWS EC2
- Amazon Linux 2023
- Linux Networking Commands
- Nginx

## Commands Used

```bash
hostname -I
ip a
ip route
cat /etc/resolv.conf
ping -c 4 8.8.8.8
ping -c 4 google.com
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl status nginx
curl http://localhost
