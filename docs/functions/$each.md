# **$each**
> **Like javascript forEach** <br/>
> $each[var;code;type?]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| Var | Unknown | String | True |
| Code | Unknown | String&lt;interpretableCode&gt; | True |
| Type | Unknown | Number[1,2] | False |

### Returns
> Void

### Example
> ```php
$var[texts;[&quot;hi&quot;, &quot;nya&quot;, &quot;ily paul banks&quot;]]
$each[texts;
	$log[EACH INFO;$var[item]]
]
```