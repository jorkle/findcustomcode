## Custom Code Finder
Find hosts with custom (non 3rd party code) while bug bounty hunting.

## Install

```bash
go install https://github.com/jorkle/customcodefinder/cmd/customcodefinder@latest
```

## Usage
```bash
cat ./subs.txt | httprobe | customcodefinder | tee interesting.txt
```



