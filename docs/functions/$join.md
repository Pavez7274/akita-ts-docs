# **$join**
> **...** <br/>
> $join[key;separator?]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| Key | The key of the array to join or a json array | String&lt;variable&gt; &#124; array | True |
| Separator | The element separator | String | False |

### Returns
> Unknown

### Example
> ```php
$var[array;["hola!", "sabias", "que", "hablo", "español?"]]
$join[array] // hola! sabias que hablo español?
$join[[1, 2, 3, 4];-] // 1-2-3-4
```