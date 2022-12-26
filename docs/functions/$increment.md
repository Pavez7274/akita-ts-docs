# **$increment**
> **Increments a numeric variable by 1** <br/>
> $increment[key;type?]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| Key | Unknown | String | True |
| Type | Unknown | &quot;prefix&quot; | &quot;postfix&quot; | False |

### Returns
> Number

### Example
> ```php
$var[index;4] $var[xedni;8]
$increment[index] // increments and return 5
$increment[xedni;postfix] // increments and return 8
```