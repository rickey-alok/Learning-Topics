# cheatsheet - CURL

Table of Content
<!-- TOC -->

- [cheatsheet - CURL](#cheatsheet---curl)
- [Request](#request)
- [Data](#data)
- [Headers](#headers)
- [Options](#options)

<!-- /TOC -->

# Request
```
-X POST          # --request
-L               # follow link if page redirects
-F 	             # --form: HTTP POST data for multipart/form-data
```

# Data
```
-d 'data'    # --data: HTTP post data, URL encoded (eg, status="Hello")
-d @file     # --data via file
-G           # --get: send -d data via get
```

# Headers

```
-A <str>         # --user-agent
-b name=val      # --cookie
-b FILE          # --cookie
-H "X-Foo: y"    # --header
--compressed     # use deflate/gzip
```

# Options
```
-o <file>    # --output: write to file
-u user:pass # --user: Authentication

-i           # --include: Include the HTTP-header in the output
-I           # --head: headers only
```
