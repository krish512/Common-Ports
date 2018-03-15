# README #

Most common ports used in servicedb file format for nmap

### What is this repository for? ###

* Quick summary:
    This repository contains most commonly used ports in servicedb file format compatible to be used with nmap

* Version 0.1
* [Repository Link](https://github.com/krish512/Common-Ports)


### How do I get set up? ###

* Requirements:
    Install nmap

* Usage (this is how I use it):
    `nmap -Pn --servicedb ./ports.list --max-retries 2 --max-rtt-timeout 500ms --min-parallelism 2 --max-parallelism 10 --open 127.0.0.1`

### Who do I talk to? ###

* Repo owner or admin:
    `Krishna Modi <krish512@hotmail.com>`
