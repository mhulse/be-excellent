#### Call:

```
<csp:object name="gStory" classname="dt.cms.schema.CMSStory" objid="28804455" />
<custom:rg:test:section object="#(gStory)#" prehtml />
<custom:rg:test:section object="#(gStory)#" />
<custom:rg:test:section object="#(gStory)#" posthtml />
```

#### Output:

```
hello !<!doctype html>
<html>
<head>
</head>
<body>
hello 4@dt.cms.schema.CMSStory!
</body>
</html>
hello !
```

#### Discussion:

[RULE, csr:section, PRE/POSTHTML, passing an object and NOT losing its context?](https://groups.google.com/d/topic/intersystems-public-cache/IU3MtavDRdM/discussion)