---
title: MetadataValidationTest
author: noelbundick
product: ['azure']
ms.author: jasoz
ms.date: 07/23/2018
ms.topic: article
ms.prod: .net
ms.technology: devlang-csharp
---
# Header Locale in link check [text](https://docs.microsoft.com/en-us)
`#1 Link in header` 

`#2 Link in paragraph`

This is paragraph for locale in inline link check [text](https://docs.microsoft.com/en-us)

This is paragraph for locale in autolink check <https://docs.microsoft.com/en-us>

This is paragraph for http security check [text](http://docs.microsoft.com/)

`#3 Link in List`

- List Item 1: locale in link check [text](https://docs.microsoft.com/en-us)
- List Item 2: http security check [text](http://docs.microsoft.com)

`#4 Link in TripleColon or Zone`

`Placeholder for zone pivot`

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

`Placehold for links in Row`

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
