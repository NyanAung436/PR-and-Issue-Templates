### If you're solving an issue 

Format

```
<type>: <subject> [<issue>]
<body> [optional, fill body if more information is needed]
<Blank Line>
<footer>
```

Sample-1

```
refactor: remove unneccessary logs [#100]
- change filelock module's log level to error level so that info level will not be shown in console

Fixed #100
```

Sample-2

```
feat: add random proxy to chrome driver [#87]
- add method for random proxy in random useragent method to prevent ip-blocking 
- add chrome extensions for proxy in secrets folder

Resolved #87
```

Sample-3

```
perf/feat: add operations and infinite search [#76]
- add infinite search method for keyword scraping
- add 5 operations using design pattern to improve algorithm performance

Resloved #76
```

### If you're solving not an issue 

Sample-1

```
bug: fix operation 3
- check if mbt_tree.allNodeName) > 10:
- check if mbt_tree.selectedNodeID != None and self.mbt_tree.selectedNodeID != "VB" 
```

Sample-2

```
docs: readme and folder paths
- update readme for new routes, sample error response and docker-compose 
- change folder name service_acc to secrets
- update error codes

```

Sample-3
```
refactor: code and file cleaning 
- remove validate_pred_string()
- remove content type detections
- remove extra function
```
