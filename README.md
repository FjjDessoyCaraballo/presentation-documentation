# Writing good documentation

## Headers with `#`

If you want to add a cool title, subtitle, or just subheaders that delimit a clear break on topic, you can use the `#` operator. If you see the raw version of this document, you will see that this title has a `#` and subsequent headers start to shrink with the addition of `#`'s.

Try it out yourself. Create a markdown file:

```bash
touch test.md
```

After that, insert these lines and check the preview:

```
# Biggest header

## Kinda big

### Getting smaller

#### and smaller

##### reaching the limit

###### limit is six #'s
```

## The most powerful showcase of the backtick "`"

The backtick (`) is a very powerful tool in your documentation process because it can single out a specific word that needs special attention. Usually it is used to emphasize a keyword, variables, function names, you call it. It should look like ``this`` if you use it at the beginning and at the end of the word. In a proper example:

```
`this` will be bold
```

Throw the example at a test markdown file and preview it to see the magic happen.

## Triple backticks gets you snippets!

If you use triple backticks you can have a snippet written down in any language you want, and markdown will color code it for you! Just add the triple backtick and a language just after - e.g. "```c" (without the parenthesis) and close it at the end of the snippet with another triple backtick. For the example below, check the raw version of the document and you will see it in action in the preview:

```c
#include <stdio.h>

int main(void)
{
  printf("HELLO WORLD\n");
  return (1);
}
```

Remember that you can do it in different languages, just specify it after the first triple backtip.

## Bold and italic

You can use bold and italic in text with `*` to get emphasize the text however you see fit:

```
*this is an example with one star*
```
*this is an example with one star*

```
**this an an example with two stars**
```
**this an example with two stars**

In sum, one star for italic, two stars for bold text.

## Lists and bullet-points

You can make quick numbered lists and bullet-points. All you have to do for a numbered list is put down the number and a dot afterwards:

```
1. one
2. two
3. three
4. four
```

And it should look like this:

1. one
2. two
3. three
4. four

For bullet-points, you can simply use a dash `-`:

```
- one
- two
- three
- four
```

- one
- two
- three
- four

## Links to any website

For links to websites, you need to use square brackets followed by parentheses `[]()`:

Put the link text inside the square brackets [link text]
Put the URL inside the parentheses (https://example.com)
```
Combined format: [link text](https://example.com)"
```

