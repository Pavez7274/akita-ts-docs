# Advanced Tips & Examples

- - -

## Invokers
> You can run native js functions in your code as follows. <br/>
> **$var[ivoke:key(->keeper)?;...arguments]**

#### Syntax
```php
$var[invoke:key(->keeper)?;...arguments?]
      |      |     |           | 
      |      |     |           |__ The arguments that are given (optional)
      |      |     |
      |      |     |__ Where save the result (optional)
      |      |
      |      |__ The path where the function is located
      |
      |__ The keyword that tells the interpreter to execute that function (ALWAYS REQUIRED)
```

#### Example
```js
$c[
    We will be making a code to see the words that start with a capital letter.
    This variable called "str" will be where our result will come from.
]
$var[str;My name is Walter Hartwell White. I live at 308 Negra Arroyo Lane, Albuquerque, New Mexico, 87104. To all law enforcement entities, this is not an admission of guilt. I am speaking to my family now. Skyler, you are the love of my life. I hope you know that. Walter Jr., you're my big man. There are going to be some things that you'll come to learn about me in the next few days. But just know that no matter how it may look, I only had you in my heart. Goodbye.]

$c[
    Now we will call the "String.prototype.match" to filter words that start with a capital letter.
    We will give it as argument /[A-Z]\w+/g, that is, any word composed only of alphabetic characters that begins with a capital letter.
    Also, we will save the result in a variable called "words".
]
$var[invoke:str.match->words;/[A-Z]\w+/g]

$c[
    It only remains to appreciate the result!!
]
$log[;$var[words]]
/*
    [ 
        'My', 'Walter', 'Hartwell', 'White',
        'Negra', 'Arroyo', 'Lane', 'Albuquerque',
        'New', 'Mexico', 'To', 'Skyler', 'Walter',
        'Jr', 'There', 'But', 'Goodbye'
        ]
*/
```