<h1><p align="center">Brute-F1</p></h1>

<p align="center">Any Website Admin Panel Finder<br/>―――― MD Asif Hasan ――――</p>

#### Features
- Multi-threading on demand
- Big path list (482 paths)
- Supports php, asp and html extensions
- Checks for potential EAR vulnerabilites
- Checks for robots.txt
- Support for custom patns

### Installation
```
git clone https://github.com/DetaSploit/Apanel-F1
```
```
cd Apanel-F1
```
### Usages
- Check all paths with php extension
```
python apanel-f1.py -u example.com --type php
```
- Check all paths with php extension with threads
```
python apanel-f1.py -u example.com --type php --fast
```
- Check all paths without threads
```
python apanel-f1.py -u example.com
```
- Adding a custom path. For example if you want all paths to start with /data (example.com/data/...) you can do this:
```
python apanel-f1.py -u example.com --path /data
```
<b>Note: </b> When you specify an extension using <b>--type</b> option, Apanel-F1 includes paths of that extension as well as paths with no extensions like <b>/admin/login</b>
