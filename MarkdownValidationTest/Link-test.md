`#1 Link in header`
# Header Locale in link check [text](https://docs.microsoft.com/en-us)

`#2 Link in paragraph`

This is paragraph for locale in inline link check [text](https://docs.microsoft.com/en-us)

This is paragraph for locale in autolink check <https://docs.microsoft.com/en-us>

This is paragraph for http security check [text](http://docs.microsoft.com/)

`#3 Link in List`

- List Item 1: locale in link check [text](https://docs.microsoft.com/en-us)
- List Item 2: http security check [text](http://docs.microsoft.com)

`#4 Link in TripleColon or Zone`

:::zone target=\"chromeless\"

Locale in link check [alt text](https://docs.microsoft.com/en-us)

:::zone-end

:::zone target=\"edge\"

http security check [alt text](http://docs.microsoft.com/)

:::zone-end

`#5 Link in Moniker range`

::: moniker range=\"product - 1.0\"

Locale in link check [alt text](https://docs.microsoft.com/en-us)

::: moniker-end

::: moniker range=\"product - 1.0\"

http security check [alt text](http://docs.microsoft.com/)

::: moniker-end

`#6 Link in LinkReferenceDefinition(Group)`

[foo]: /url1 \"title\"

Locale in link check [alt text](https://docs.microsoft.com/en-us), [foo]

[foo]: /url1 \"title\"

http security check [alt text](http://docs.microsoft.com/), [foo]

`#7 Link in TabGroup`

Tab group test case

## [title-a](#tab/a)

Locale in link check [alt text](https://docs.microsoft.com/en-us)

## [title-b](#tab/b)

http security check [alt text](http://docs.microsoft.com/)

`#8 Link in Row`

:::row:::

:::column:::

Locale in link check [alt text](https://docs.microsoft.com/en-us)

:::column-end:::

:::row-end:::

:::row:::

:::column:::

http security check [alt text](https://docs.microsoft.com/)

:::column-end:::

:::row-end:::

`#9 Link in block quote`

> Locale in link check [alt text](https://docs.microsoft.com/en-us)

> http security check [alt text](http://docs.microsoft.com/)

`#10 Link in Html block`

<p>Locale in link check [alt text](https://docs.microsoft.com/en-us)</p>

<p>http security check [alt text](https://docs.microsoft.com)</p>

`#11 Link in Fenced code or inline code (not applicable)`

```
Locale in link check [alt text](https://docs.microsoft.com/en-us)

```

```
http security check [alt text](http://docs.microsoft.com)

```