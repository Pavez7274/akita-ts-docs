# **$call**
> **...** <br/>
> $callback[name;...params]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| Name | Unknown | String | True |
| ...params | Unknown | T | True |

### Returns
> Unknown

### Example
> ```php
// client.addCallback(&quot;test&quot;, &quot;$log[TEST;hi $1!!]&quot;)
$call[test;Pavez] // TEST ;; hi Pavez!!
```