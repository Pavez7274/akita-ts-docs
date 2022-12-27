# **$var**
> **Add or get a variable** <br/>
> $var[key;value?;type?]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| Key | Unknown | String | True |
| Value | Unknown | Any | True |
| Type | Unknown | &quot;unknown&quot; &#124; &quot;string&quot; &#124; &quot;number&quot; &#124; &quot;bigint&quot; &#124; &quot;regexp&quot; &#124; &quot;json&quot; | True |

### Returns
> String

### Example
> ```php
$var[str;hi, im a string] // string var
$var[num;4] // number var
$var[obj;{ "leif": "erikson" }] // object var
```