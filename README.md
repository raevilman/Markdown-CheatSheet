# Markdown-Cheatsheet  

* [Character Styles](https://github.com/raevilman/Markdown-CheatSheet#character-styles)  
* [Block Quotes](https://github.com/raevilman/Markdown-CheatSheet#blockquotes)  
* [Headers](https://github.com/raevilman/Markdown-CheatSheet#h1-heading)  
* [Lists](https://github.com/raevilman/Markdown-CheatSheet#lists)  
* [Tables](https://github.com/raevilman/Markdown-CheatSheet#tables)  
* [Links](https://github.com/raevilman/Markdown-CheatSheet#links)  
* [Images](https://github.com/raevilman/Markdown-CheatSheet#images)  
* [Horizontal Rule](https://github.com/raevilman/Markdown-CheatSheet#hr)  
# Character Styles  

|Example | Name | Syntax | Description
| :---: | :---: | :---: | :---: |
|__I am bold__ | Bold | \__I am bold\__ <br/> \*\*I am bold\*\* | Use double underscores or double asterisks
|_I am italic_ | Italic | \_I am italic\_ <br/> \_I am italic\_ | Use single underscore or single asterisk
|*Combine **both*** | | \*Combine \*\*both\*\*\* ||
|~~I am hurt~~ | Strikethrough | \~\~I am hurt\~\~ | Use double tilde
|4<sup>th</sup> | Superscript | 4&lt;sup&gt;th&lt;/sup&gt; | Use &lt;sup&gt; tag
|H<sub>2</sub>O | Subscript | H&lt;sub&gt;2&lt;/sub&gt;O | Use &lt;sub&gt; tag

---
# Blockquotes  
Now, lets try quoting:
> Looks nice!   

Name: Blockquotes  
Syntax: \> Looks nice!  
Description: Use greater-than symbol '>'

hmm, How about a nested quote:
>> Wow, it worked!   

Name: Nested Blockquotes  
Syntax: \>\> Wow, it worked!  
Description: Use two greater-than symbol '>'

:wink: another level:
>>> Deep thought!   

Name: Nested Blockquotes  
Syntax: \>\>\> Deep thought!  
Description: Use three greater-than symbol '>'

`Tip:Number of '>' symbols decide the depth of blockquotes`  


---
# h1 Heading
Name: h1 Heading  
Syntax: \# h1 Heading  
Description: Use hashtag  

## h2 Heading
Name: h2 Heading  
Syntax: \#\# h2 Heading  
Description:  Use two hashtags  

### h3 Heading
Name: h3 Heading  
Syntax: \#\#\# h3 Heading  
Description:  Use three hashtags  

#### h4 Heading
Name: h4 Heading  
Syntax: \#\#\#\# h4 Heading  
Description:  Use four hashtags  

##### h5 Heading
Name: h5 Heading  
Syntax: \#\#\#\#\# h5 Heading  
Description:  Use five hashtags  

###### h6 Heading
Name: h6 Heading  
Syntax: \#\#\#\#\#\# h6 Heading  
Description:  Use six hashtags  

``Note``: Make sure you have a blank line above the header line

---

# Lists

* Item 1
* Item 2
* Item 3  

Name: Bulleted List  
Syntax: \* Item 1    
Description: Use asterisk  

 1. Item 1
 2. Item 2
 3. Item 3  


 Name: Numbered List  
 Syntax: 1. Item 1    
 Description: Use asterisk  


 1. Item 1  
 2. Item 2  
  * Item 2a
  * Item 2b  
 3. Item 3  


 Name: Nested List  
 Syntax: .* Item 2a  
 Description: Dot in above Syntax represents space  


 - [x] Completed item
 - [ ] Incomplete item  



  Name: Tasks List  
  Syntax: \- [x] Completed item  
  \- [ &nbsp;] Incomplete item  
  Description: Use Hyphen *space* Square Brackets   

  ---

# Tables  

| Head1 (Left-aligned) | Head2 (Center-aligned) | Head3 (Right-aligned)
| :---     |   :---: | ---:
| Cell 1:1 | Cell 1:2
| Cell 2:1 | Cell 2:2 | Cell 2:3
| Cell 3:1 | Cell 3:2  

Name: Tables  
Syntax: Above table is rendered with below code  
```
| Head1 (Left-aligned) | Head2 (Center-aligned) | Head3 (Right-aligned)
| :---     |   :---: | ---:
| Cell 1:1 | Cell 1:2
| Cell 2:1 | Cell 2:2 | Cell 2:3
| Cell 3:1 | Cell 3:2 |
```
Description: Use hyphens to create headers and pipes to separate cells.  
Manage alignment with `:` to left, both or right side of the hyphens in header row.  


---  
# Links

[This is a link](https://github.com/raevilman/Markdown-CheatSheet "Go to Markdown-CheatSheet")  

Syntax for above example:  
\[This is a link\]\(https://github.com/raevilman/Markdown-CheatSheet)  

Name: Links  
Syntax: \[Label or text for link\]\(URL\)  
Description:  Place text/label for link in square brackets and then place actual URL in parentheses  

For `tooltip`, on hovering over the link e.g. [Hover on me](https://github.com/raevilman/Markdown-CheatSheet "I'm a tooltip")  
You can optionally mention title text in double quotes in parentheses after the URL separated by space
Syntax for 'Hover on me' example is as below:  
\[Hover on me\]\(https://github.com/raevilman/Markdown-CheatSheet "I'm a tooltip")  

---
# Images  
Syntax:  

Inline-style:  
```  
![alt text](https://github.com/raevilman/Markdown-CheatSheet/raw/master/assets/images/Pizza_Love.jpg "I Love Pizza")
```
Reference-style:  
```
![alt text][logo]

[logo]: https://github.com/raevilman/Markdown-CheatSheet/raw/master/assets/images/Emptiness.jpg "Emptiness"  
```

#### Inline-style:  


![alt text](https://github.com/raevilman/Markdown-CheatSheet/raw/master/assets/images/Pizza_Love.jpg "I Love Pizza")

#### Reference-style:  


![alt text][logo]

[logo]: https://github.com/raevilman/Markdown-CheatSheet/raw/master/assets/images/Emptiness.jpg "Emptiness"  

---  
# Horizontal Rule  

```
Use three or more of

Hyphens  

---

Asterisks

***

Underscores

___
```  
Use three or more of

Hyphens  

---

Asterisks

***

Underscores

___  
