## Tables

Create a table by assembling a list of words and separating each column with a pipe `|`. Separate the first row (the column headers) from the other rows with a series of hyphens `-`.

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

<h5 class="text-muted">RESULT</h5>

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

For aesthetic purposes, you can also add extra pipes on the ends.

```
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
```

<h5 class="text-muted">RESULT</h5>

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Note that the hyphens at the top don't need to match the length of the header text.

```
| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |
```

<h5 class="text-muted">RESULT</h5>

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

You can also include other pieces of Markdown such as links, bold, italics, or strikethroughs.

```
| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |
```

<h5 class="text-muted">RESULT</h5>

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

Finally, by adding colons `:` to lines of hyphens, you can make all text in the column left-aligned, right-aligned, or center-aligned.

```
| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
```

<h5 class="text-muted">RESULT</h5>

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |

A colon on the left side indicates a left-aligned column; a colon on the right side indicates a right-aligned column; a colon on both sides indicates a center-aligned column.
