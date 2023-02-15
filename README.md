# Fastrecon

  Fastrecon is a simple bash script that do automation for the initial reconnaissance of the target .
  
 
![This is an image](https://github.com/iHassn/Fastrecon/blob/main/.Usage.png)

## Setup
To install EasyRecon, clone this repository. EasyRecon relies on a couple of tools to be installed so make sure you have them:
* [subfinder](https://github.com/projectdiscovery/subfinder)
* [httpx](https://github.com/projectdiscovery/httpx)
* [waybackurls](https://github.com/tomnomnom/waybackurls)
 
Please make sure that as most of these tools are written in Go ,that you have Go installed and configured properly, also make sure to add the path of those tools to your PATH env

## Feature
* Enumerate all the existing domains with subfinder 
* Separate live domains from all existing domains
* Fetching all the URLs/Links from the web archive
* Getting the Javascript files 
* Remove useless URLs and sort the output 
* Extract all Possible URL's Parameters & endpoint


## Installation
```
▶ git clone https://github.com/iHassn/Fastrecon.git
```
```
▶ chmod +x Fastrecon.sh
```
```
▶./Fastrecon.sh
```
## Usage 
is simple pretty easy
./Fastrecon.sh domain.com
