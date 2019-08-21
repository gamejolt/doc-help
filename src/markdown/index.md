# A Markdown Primer

Using Markdown allows you to write in an easy-to-read plain-text format which is automatically converted into HTML. Markdown is powerful enough to do just about anything you need it to, and the resulting HTML is compatible with pretty much every device out there.

Markdown is a cinch to learn. You can use the cheat sheet below to familiarize yourself with the most commonly used elements.

## Paragraphs

A line break equals a line break. Two line breaks will make a new paragraph. To create separate paragraphs, simply leave a blank line between blocks of text.

```
This is one paragraph, and it's amazing.

And this is another paragraph!
```

<h5 class="text-muted">RESULT</h5>

This is one paragraph, and it's amazing.

And this is another paragraph!

## Headings

Create headings by placing 1 to 6 hashes `#` in front of your header text. Use 1 `#` for an H1 (the biggest), use 2 `##` for an H2 (the next biggest), and so on.

```
# This is an H1
## This is an H2
###### This is an H6
```

<h5 class="text-muted">RESULT</h5>

# This is an H1

## This is an H2

###### This is an H6

## Text Styling

#### Emphasis

Wrap text in asterisks `*` to _italicize_ it. Put double asterisks `**` around text to make it **bold**.

```
Hey, here is something *italicized* and here is some other thing **bold**.
```

<h5 class="text-muted">RESULT</h5>

Hey, here is something _italicized_ and here is some other thing **bold**.

Alternatively, you can use underscores `_` instead of asterisks `*`. This can help with double-styling pieces of text.

```
__I want this whole sentence bold, but only *this part* to be italicized and bold.__ This part won't have any emphasis added.
```

<h5 class="text-muted">RESULT</h5>

**I want this whole sentence bold, but only _this part_ to be italicized and bold.** This part won't have any emphasis added.

#### Deletion

Wrap your text in double tildes `~~` to add a strikethrough.

```
I would love to make ~~a game~~ money.
```

<h5 class="text-muted">RESULT</h5>

I would love to make ~~a game~~ money.

## Links

Create a link by wrapping square brackets `[ ]` around the clickable text. Put the URL immediately after that in parantheses `( )`.

```
Check out [this link](https://gamejolt.com)!
```

<h5 class="text-muted">RESULT</h5>

Check out [this link](https://gamejolt.com)!

Also, any text that is not wrapped but looks like a link will automatically become one. Cool, huh?

```
Head on over to https://gamejolt.com
```

<h5 class="text-muted">RESULT</h5>

Head on over to <a href="https://gamejolt.com">https://gamejolt.com</a>

## Images

You can add an image from the web to your comment using this format:

```
![alt text](imageurl.gif)
```

<h5 class="text-muted">RESULT</h5>

![alt text](./111o2di.gif)

Start the line with an exclamation point `!` followed by some alt text in brackets `[ ]`. Next comes the image's URL in parentheses `( )`.

The alt text should be a very brief description of the image. It's used by search engines and in some cases when images are not displayed, such as when a visually impaired person uses a screen reader.

## Lists

Make lines of text into a bulleted list by placing a dash `-` or an asterisk `*`, followed by a space, before each line.

```
- This is a list item.
- Another list item.
* Still part of the list.
```

<h5 class="text-muted">RESULT</h5>

- This is a list item.
- Another list item.

* Still part of the list.

#### Numbered Lists

Make a numbered list by simply starting each line with a number followed by a period `.` and a space.

```
1. This is the first item.
1. This is the second item.
1. Notice that we can use any number...
4. and the list will automatically be renumbered correctly.
```

<h5 class="text-muted">RESULT</h5>

1. This is the first item.
1. This is the second item.
1. Notice that we can use any number...
1. and the list will automatically be renumbered correctly.

## Block Quotes

You can create block quotes by prefixing lines with angle brackets `>`.

```
> This is a block quote.

> And this is still part of the block quote.
> > You can even nest block quotes within one another!
```

<h5 class="text-muted">RESULT</h5>

> This is a block quote.

> And this is still part of the block quote.
>
> > You can even nest block quotes within one another!

## Horizontal Lines

You can add a horizontal separator line between sections of content by placing three or more hyphens `-`, asterisks `*`, or underscores `_` on a line by themselves.

```
This is a bit of text.

***

Separated, oh no!
```

<h5 class="text-muted">RESULT</h5>

This is a bit of text.

Separated, oh no!

## Code

#### Inline Code

You can add inline code tags to any piece of text by putting a backtick <code>`</code> on each side. The designated text will be displayed using a special fixed-width font.

```
Tweet out jam activity with the hashtag `#blahjam` if you want to be nice.
```

<h5 class="text-muted">RESULT</h5>

Tweet out jam activity with the hashtag `#blahjam` if you want to be nice.

#### Fenced Code

You can create a fenced block of code by preceding it and following it with a line of three apostrophes <code>```</code>.

<pre><code>And here's how you annoy someone with JavaScript...

```
while ( true ) {
confirm( 'Do you like turtles?' );
}
```</code></pre>

<h5 class="text-muted">RESULT</h5>

And here's how you annoy someone with JavaScript...

```
while ( true ) {
confirm( 'Do you like turtles?' );
}
```
