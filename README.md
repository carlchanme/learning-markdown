# Markdown basic commands

| Syntax      | Description                 |                       |
|-------------|-----------------------------|-----------------------|
| Heading 1   | #                           | #                     |
| Heading 2   | ##                          | ##                    |
| Heading 3   | ###                         | ###                   |
| Italics     | \*italics*                  | *italic*              |
| Bold        | \*\*Bold**                  | **Bold**              |
| Strike      | \~\~Strike~~                | ~~Strike~~            |
| Block quote | >                           | >                     |
| Links       | \[link name](link.com)      | [link name](link.com) |
| Code Block  | \`code here`                | `code here`           |
| Unorderlist | *List item <br/> *List item |                       |

## Shell
```shell
if [ -z $SERVER ] || [ -z $DATE]; then
  echo "Please specify both server and date";
  exit 1;
fi;
```

### HTML
```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
</body>
</html>
```

### Javascript
```javascript
while (i<10) {
    text+= "The number is" + i;
    i++;
}
```

### Python
```python
thislist = ["apple", "banana", "cherry"]
print(thislist)
```


## Escape characters in markdown
If you want the browser to ignore the syntax and retain the characters, the characters can be escaped using the backslash \.

For instance, \* would not parse its succeeding characters as italics.
