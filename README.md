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
