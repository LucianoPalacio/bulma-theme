---
layout: post
title: Markup - HTML Tags and Formatting
categories:
    - Markup
comments: true
permalink: html-tags-formatting.html
---

A variety of common markup showing how the theme styles them.

# Header one

## Header two

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Stay hungry. Stay foolish.

Multi line blockquote with a cite reference:

> People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying no to 1,000 things.

<cite>Steve Jobs</cite> --- Apple Worldwide Developers' Conference, 1997
{: .small}

## Tables

| Employee         | Salary |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | $1     | Because that's all Steve Jobs needed for a salary.           |
| [Jane Doe](#)    | $100K  | For all the blogging she does.                               |
| [Fred Bloggs](#) | $100M  | Pictures are worth a thousand words, right? So Jane × 1,000. |
| [Jane Bloggs](#) | $100B  | With hair like that?! Enough said.                           |

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Unordered Lists (Nested)

  * List item one
      * List item one
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one
      1. List item one
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.button` class.

```html
<a href="#" class="button is-success">Success Button</a>
```

[Primary Button](#){: .button .is-primary}
[Success Button](#){: .button .is-success}
[Warning Button](#){: .button .is-warning}
[Danger Button](#){: .button .is-danger}
[Info Button](#){: .button .is-info}
[White Button](#){: .button .is-white}
[Light Button](#){: .button .is-light}
[Dark Button](#){: .button .is-dark}
[Black Button](#){: .button .is-black}
[Link Button](#){: .button .is-link}

```markdown
[Primary Button](#){: .button .is-primary}
[Success Button](#){: .button .is-success}
[Warning Button](#){: .button .is-warning}
[Danger Button](#){: .button .is-danger}
[Info Button](#){: .button .is-info}
[White Button](#){: .button .is-white}
[Light Button](#){: .button .is-light}
[Dark Button](#){: .button .is-dark}
[Black Button](#){: .button .is-black}
[Link Button](#){: .button .is-link}
```

[Large Button](#){: .button .is-large}
[Medium Button](#){: .button .is-medium}
[Normal Button](#){: .button}
[Small Button](#){: .button .is-small}

```markdown
[Large Button](#){: .button .is-large}
[Medium Button](#){: .button .is-medium}
[Normal Button](#){: .button}
[Small Button](#){: .button .is-small}
```

[Outlined](#){: .button .is-outlined}
[Outlined](#){: .button .is-primary .is-outlined}
[Outlined](#){: .button .is-info .is-outlined}
[Outlined](#){: .button .is-success .is-outlined}
[Outlined](#){: .button .is-danger .is-outlined}
[Outlined](#){: .button .is-warning .is-outlined}

```markdown
[Outlined](#){: .button .is-outlined}
[Outlined](#){: .button .is-primary .is-outlined}
[Outlined](#){: .button .is-info .is-outlined}
[Outlined](#){: .button .is-success .is-outlined}
[Outlined](#){: .button .is-danger .is-outlined}
[Outlined](#){: .button .is-warning .is-outlined}
```

[Loading](#){: .button .is-primary .is-loading}

```markdown
[Loading](#){: .button .is-primary .is-loading}
```

## Notification

You can also add notifications by appending `{: .notification}` to a paragraph.
{: .notification}

You can also add notifications by appending `{: .notification .is-primary}` to a paragraph.
{: .notification .is-primary}

You can also add notifications by appending `{: .notification .is-info}` to a paragraph.
{: .notification .is-info}

You can also add notifications by appending `{: .notification .is-success}` to a paragraph.
{: .notification .is-success}

ou can also add notifications by appending `{: .notification .is-warning}` to a paragraph.
{: .notification .is-warning}

You can also add notifications by appending `{: .notification .is-danger}` to a paragraph.
{: .notification .is-danger}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://apple.com "Apple"){:target="_blank"}.

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
	margin: 0 0 5px;
	font-weight: bold;
	font-size: 38px;
	line-height: 1.2;
	and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Albert Einstein's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.