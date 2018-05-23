# Umbrella Category Lookup

## Purpose
I created this tool to aid in researching why a given domain is being blocked by Cisco Umbrella.  
It will retern all categories that a domain is tagged under as well as the Security Category if there is one.

## Example
```
$ ./ucl google.com
"Search Engines"
```

OR  

```
$ ./ucl microsoft.com
"Software/Technology"
"Business Services"
```

OR  

```
$ ./ucl freetrojanbotnet.com
"Enterprise Malware"
```

### Source
The Umbrella help doc that inspired this script:  
https://support.umbrella.com/hc/en-us/articles/360000085403
