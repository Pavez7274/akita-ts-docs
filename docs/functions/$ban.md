# **$ban**
> **Bans a user** <br/>
> $ban[user;options?;guild?]
- - -

### Fields
| name | description | type | required |
|------|-------------|------|----------|
| User | Unknown | Snowflake&lt;user&gt; | True |
| Options | Unknown | HJSOEncodable | False |
| Guild | Unknown | Snowflake&lt;guild&gt; | False |

### Returns
> Boolean

### Example
> ```php
$ban[$author[id];{ reason: "idk..." }]
```