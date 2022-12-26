# **$push**
> **Like Array.push** <br/>
> $push[key;...items]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| Key | Unknown | String | True |
| ...items | Unknown | Any | True |

### Returns
> Number

### Example
> ```php
$var[array;[1, 2, 3]]
$push[array;5;6]
$log[;$var[array]] // [1, 2, 3, 4, 5, 6]
```