# Apanel-F1
find admin login pages and EAR vulnerabilites.

#### Features
- Multi-threading on demand
- Big path list (482 paths)
- Supports php, asp and html extensions
- Checks for potential EAR vulnerabilites
- Checks for robots.txt
- Support for custom patns

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
