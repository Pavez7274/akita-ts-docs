# **$push**
> **Adds elements to the end of an array and returns the new length (this mutates the array** <br/>
> $push[key;...items]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| Key | Unknown | String&lt;variable&gt; | True |
| ...items | Unknown | Any | True |

### Returns
> Number

### Example
> ```php
$var[array;[1, 2, 3]]
$push[array;5;string:6]
$log[;$var[array]] // [1, 2, 3, 4, 5, "6"]
```