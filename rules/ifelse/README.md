#### Call:

```
<custom:rg:test:ifelse>
	
	<p>IF 1</p>
	
<custom:rg:else>
	
	<p>ELSE 1</p>
	
</custom:rg:test:ifelse>

<hr>

<custom:rg:test:ifelse boolean>
	
	<p>IF 2</p>
	
<custom:rg:else>
	
	<p>ELSE 2</p>
	
</custom:rg:test:ifelse>
```

#### Output:

> <p>IF 1</p>
> <hr>
> <p>ELSE 2</p>

#### Discussion:

[Possible to have an "ELSE" if RULE can't LOOP?](https://groups.google.com/d/topic/intersystems-public-cache/abztVTDwxdE/discussion)