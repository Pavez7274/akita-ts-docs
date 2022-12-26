# **$var**
> **Add or get a variable** <br/>
> $var[key;value?;type?]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| Key | Unknown | String | True |
| Value | Unknown | Any | True |
| Type | Unknown | &quot;unknown&quot; | &quot;string&quot; | &quot;number&quot; | &quot;bigint&quot; | &quot;regexp&quot; | &quot;json&quot; | True |

### Returns
> String

### Example
> ```php
$var[str;hi, im a string] // string var
$var[num;4] // number var
$var[obj;{ &quot;leif&quot;: &quot;erikson&quot; }] // object var
```