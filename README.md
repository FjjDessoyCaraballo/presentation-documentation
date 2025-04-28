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

Put the link text inside the square brackets `[link text]`
Put the URL inside the parentheses `(https://example.com)`
```
Combined format: [link text](https://example.com)"
```

## Tables

Doing tables is the one tricky thing in markdown because it requires some attention. You have to first use the vertical bar `|` separating each column in the first row which will be for your column headers of the table. Afterwards, you will write the same vertical bars but the content between bars will be filled with dashes `-`. The third and last row will then contain the row headers in the first column, and whatever content you desire in the rest of the cells. It sounds like a lot because it is a lot, but here's an example:

```
| header1 | header2 | header3 | header4 |
| ------- | ------- | ------- | ------- |
| price | 1.5 | 2.5 | 3.5 |
| inflation | 2% | 2.5% | 0.8% |
| reason | NA | NA | NA |
```

This will be the result in markdown:

| header1 | header2 | header3 | header4 |
| ------- | ------- | ------- | ------- |
| price | 1.5 | 2.5 | 3.5 |
| inflation | 2% | 2.5% | 0.8% |
| reason | NA | NA | NA |

As you can see, everything will fit nicely, even if you do not put proper spaces between the vertical bars. You can, and maybe should, make your strings bold or italic depending on necessity to help in your table visualizing. You can also add link within it, especially if you are referencing stuff within your table.

## Referencing headers and subheaders with links

This one feature is only effective in GitHub, but you can copy links to headers and subheader within the same page to "fast-forward" to specific parts of the document. The syntax is no different from forming a webpage link. Below we will have bullet-points with different links to this same document:

- [Header section](https://github.com/FjjDessoyCaraballo/presentation-documentation/tree/main?tab=readme-ov-file#headers-with-)
- [Backtick section](https://github.com/FjjDessoyCaraballo/presentation-documentation/tree/main?tab=readme-ov-file#the-most-powerful-showcase-of-the-backtick-)
- [Triple backtick section](https://github.com/FjjDessoyCaraballo/presentation-documentation/tree/main?tab=readme-ov-file#triple-backticks-gets-you-snippets)
- [Text formatting](https://github.com/FjjDessoyCaraballo/presentation-documentation/tree/main?tab=readme-ov-file#bold-and-italic)
- [List and bullet-points section](https://github.com/FjjDessoyCaraballo/presentation-documentation/tree/main?tab=readme-ov-file#lists-and-bullet-points)
- [Links and website](https://github.com/FjjDessoyCaraballo/presentation-documentation/tree/main?tab=readme-ov-file#links-to-any-website)
- [Tables](https://github.com/FjjDessoyCaraballo/presentation-documentation/blob/main/README.md#tables)

The easiest way to get these quick references to your own documentation is to click the chainlink in the document and copying the link that appears in your browser.
