# **$join**
> **...** <br/>
> $join[key;separator?]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| Key | Unknown | String&lt;variable&gt; | array | True |
| Separator | Unknown | String | False |

### Returns
> Unknown

### Example
> ```php
$var[array;[&quot;hola!&quot;, &quot;sabias&quot;, &quot;que&quot;, &quot;hablo&quot;, &quot;español?&quot;]]
$join[array] // hola! sabias que hablo español?
$join[[1, 2, 3, 4];-] // 1-2-3-4
```