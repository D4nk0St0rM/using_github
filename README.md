[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Press+Start&size=30&duration=4000&color=1E0DC6EE&center=true&vCenter=true&multiline=true&width=1200&height=150&lines=D4nk0St0rM;SpReAd+L0vE+%26+ShArE+Kn0wLeDgE;%60I'm+smart+enough+to+know+that+I'm+dumb%60)](https://git.io/typing-svg)
---
____
### using github
Summary for github use

#### Text Formating
```
# HEADING 1
## HEADING 2
###### HEADING 6
```
**Bold**
```
**Bold**
__Bold__	
```
*Italic*
```
*Italic*
_Italic_	
```
~~Strikethrough~~
```
~~Strikethrough~~
```
**Bold and _nested_ italic**
```
**Bold and _nested_ italic**
```

***All bold and italic***
```
***All bold and italic***
```

> Quoted Text
```
> Quoted Text
```

#### Links
This guide was summarised from [docs.github](https://docs.github.com)
```
This guide was summarised from [docs.github](https://docs.github.com)
```
> Relative links
```
If you have a README file in root of your repository, another file in docs/CONTRIBUTING.md

[Contribution guidelines for this project](docs/CONTRIBUTING.md)

You can use all relative link operands, such as ../

```


#### Code formating

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

#### images
When you want to display an image which is in your repository use relative links
```
../blob/main/assets/images/eff_monogram-red-reverse.png
```
![GitHub Dark](https://www.eff.org/files/2018/06/14/eff_monogram-red-reverse.png)

```
![GitHub Dark](https://www.eff.org/files/2018/06/14/eff_monogram-red-reverse.png)
```

#### Tables
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

```
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
```
> Table Alignment

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```


#### Git Commands
```
sudo git clone 
sudo git status
sudo git add
sudo git commit
sudo git pull origin master 
```

#### Lists

You can make an unordered list by preceding one or more lines of text with - or *.

- George Washington
- John Adams
- Thomas Jefferson

```
- George Washington
- John Adams
- Thomas Jefferson
```


To order your list, precede each line with a number.

1. James Madison
2. James Monroe
3. John Quincy Adams

```

1. James Madison
2. James Monroe
3. John Quincy Adams

```

#### Nested Lists

You can create a nested list by indenting one or more list items below another item.

To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Atom, you can align your list visually. Type space characters in front of your nested list item, until the list marker character (- or *) lies directly below the first character of the text in the item above it.

1. First list item
   - First nested list item
     - Second nested list item

```
1. First list item
   - First nested list item
     - Second nested list item
```
     
To create a nested list in the comment editor on GitHub, which doesn't use a monospaced font, you can look at the list item immediately above the nested list and count the number of characters that appear before the content of the item. Then type that number of space characters in front of the nested list item.

In this example, you could add a nested list item under the list item 100. First list item by indenting the nested list item a minimum of five spaces, since there are five characters (100. ) before First list item.

100. First list item
     - First nested list item
```

100. First list item
     - First nested list item

```
You can create multiple levels of nested lists using the same method. For example, because the first nested list item has seven characters (␣␣␣␣␣-␣) before the nested list content First nested list item, you would need to indent the second nested list item by seven spaces.

100. First list item
     - First nested list item
       - Second nested list item
```
100. First list item
     - First nested list item
       - Second nested list item
```
#### Task lists

To create a task list, preface list items with a hyphen and space followed by [ ]. To mark a task as complete, use [x].

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```

If a task list item description begins with a parenthesis, you'll need to escape it with \:

- [ ] \(Optional) Open a followup issue
```

- [ ] \(Optional) Open a followup issue

```

#### Creating a collapsed section

You can temporarily obscure sections of your Markdown by creating a collapsed section that the reader can choose to expand. 

For example, when you want to include technical details in an issue comment that may not be relevant or interesting to every reader, you can put those details in a collapsed section. 

Any Markdown within the ```<details>``` block will be collapsed until the reader clicks to expand the details. 

Within the ```<details>``` block, use the ```<summary>``` tag to create a label to the right of icon

```
<details><summary>CLICK ME</summary>
<p>

#### We can hide anything, even code!

    ```ruby
      puts "Hello World"
    ```

</p>
</details>
```

<details><summary>CLICK ME</summary>
<p>

#### We can hide anything, even code!

    ```ruby
      puts "Hello World"
    ```

</p>
</details>

The Markdown will be collapsed by default.



