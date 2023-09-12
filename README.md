<details>
<summary> Headings </summary>

```
# A first-level heading
## A second-level heading
### A third-level heading
```
# A first-level heading
## A second-level heading
### A third-level heading

</details>


---
<details>
<summary>Styling text</summary>

 | Style | Syntax | Keyboard shortcut | Example | Output |
 |-------|------|-----|------|----|
 | Bold | ** ** or __ __ | Command+B (Mac) or Ctrl+B (Windows/Linux) | `**This is bold text**` | **This is bold text** | 
 | Italic | * * or _ _ | 	Command+I (Mac) or Ctrl+I (Windows/Linux) | 	`_This text is italicized_ ` | 	This text is italicized | 
 | Strikethrough | 	~~ ~~ |  	None | 	`~~This was mistaken text~~` | 	~~This was mistaken text~~ | 
 | Bold and nested italic | 	** ** and _ _ | 	None | 	`**This text is _extremely_ important**` | 	**This text is _extremely_ important** | 
 | All bold and italic | 	*** *** | 	None | ```***All this text is important***``` | 	***All this text is important*** | 
 | Subscript | 	<sub> </sub> | 	None | 	```This is a <sub>subscript</sub>``` | his is a <sub>subscript</sub> | 
 | Superscript | 	<sup> </sup> | 	None | 	```This is a <sup>superscript</sup>``` |  This is a <sup>superscript</sup> | 


</details>

---
 
<details>
<summary>Adding a table</summary>
  
```
| Rank |  THING-TO-RANK | 
|-----:|---------------|
|     1|               | 
|     2|               | 
|     3|               | 
```
| Rank |  THING-TO-RANK | 
|-----:|---------------|
|     1|               | 
|     2|               | 
|     3|               | 


<details>
<summary> Formatting content within your table </summary>

```
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

To include a pipe `|` as content within your cell, use a `\` before the pipe:
```
| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |

```
| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |


</details>


</details>

---
<details>
<summary>Adding a collapsed section</summary>

```
<details>
<summary>My top THINGS-TO-RANK</summary>

YOUR TABLE

</details>
```
<details>
<summary>My top THINGS-TO-RANK</summary>

YOUR TABLE

</details>

</details>

---

<details>
<summary>Quoting code</summary>

+ For a single line -  \` `

Use \`git status` to list all new or modified files that haven't yet been committed.

Use `git status` to list all new or modified files that haven't yet been committed.

+ For multiple lines -  \``` ```

Some basic Git commands are:
\```
git status
git add
git com
\```
Some basic Git commands are:
```
git status
git add
git commit
```
To display triple backticks in a fenced code block, wrap them inside quadruple backticks.
+ use - \```` ````
  + **If you want examples see these files code line 137 to 143**
<details>
<summary> Syntax highlighting </summary>

````
```ruby
require 'red carpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
````
 
```ruby
require 'red carpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
</details>

</details>

---

<details>
<summary>Adding a quote</summary>

```
--- 
> We can push through anything if we pull together and commit ourselves.

— Mona the Octocat
```
--- 
> We can push through anything if we pull together and commit ourselves.

— Mona the Octocat

</details>

---

<details>
<summary>Adding a comment</summary>

```
<!-- COMMENT -->
<!-- TO DO: add more details about me later -->
```
<!-- COMMENT -->
<!-- TO DO: add more details about me later -->


</details>

---

<details>
<summary>Import Image</summary>

 
```
<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://github-production-user-asset-6210df.s3.amazonaws.com/117109051/258728082-1960cd31-f9c9-42b5-b6d3-000fa4c11ada.jpg">
 <sourc media="(prefers-color-scheme: light)" srcset="https://github-production-user-asset-6210df.s3.amazonaws.com/117109051/258714568-cbe93b22-5c78-471b-8d2e-1f8bbebbd1a8.png">
 <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/117109051/258714568-cbe93b22-5c78-471b-8d2e-1f8bbebbd1a8.png">
</picture>
```
<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://github-production-user-asset-6210df.s3.amazonaws.com/117109051/258728082-1960cd31-f9c9-42b5-b6d3-000fa4c11ada.jpg">
 <source media="(prefers-color-scheme: light)" srcset="https://github-production-user-asset-6210df.s3.amazonaws.com/117109051/258714568-cbe93b22-5c78-471b-8d2e-1f8bbebbd1a8.png">
 <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/117109051/258714568-cbe93b22-5c78-471b-8d2e-1f8bbebbd1a8.png">
</picture>

</details>

---

<details>
  <summary>Supported color models </summary>
  
| Color | Syntax | Example |
|---|--|--|
| HEX | `#RRGGBB` | `#0969DA` |
| RGB | `rgb(R,G,B)` | `rgb(9,105,218)` | 
| HSL	| `hsl(H,S,L)` | `hsl(212,92%,45%)` |

  
</details>

---

<details>
<summary> Links </summary>
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ).
  
```
This site was built using [GitHub Pages](https://pages.github.com/).
<a href="https://github-production-user-asset-6210df.s3.amazonaws.com/117109051/258714568-cbe93b22-5c78-471b-8d2e-1f8bbebbd1a8.png" target="_blank">GitHub Logo</a>
```
This site was built using [GitHub Pages](https://pages.github.com/).

<a href="https://github-production-user-asset-6210df.s3.amazonaws.com/117109051/258714568-cbe93b22-5c78-471b-8d2e-1f8bbebbd1a8.png" target="_blank">GitHub Logo</a>
</details>

---

<details>
<summary> list </summary>
+unordered list

  ```
- George Washington
* John Adams
+ Thomas Jefferson
```
- George Washington
* John Adams
+ Thomas Jefferson

order your lis
```
1. James Madison
1. James Monroe
1. John Quincy Adams
```
1. James Madison
1. James Monroe
1. John Quincy Adams

Nested Lists
```
1. First list item
   - First nested list item
     - Second nested list item
1. First list item
   - First nested list item
     - Second nested list item
```
1. First list item
   - First nested list item
   - Second nested list item
1. First list item
   - First nested list item
     - Second nested list item

</details>

---
<details>
<summary> Task lists </summary>
  
  ```
  - [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
  ```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
</details>

---
