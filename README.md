# HTML

## Pair Tags 

# Pre Tag 
1. it is used to display the text as-it is, along with space and line breaks
2. it is pair tag 

### Syntax 
```
<pre>text here </pre>
```

#### Sample Code 
```
<pre>
One    


Two


Three 

</pre>
```


# abbr
1. attribute are the deatils about the tag
2. it is pair tag
3. we have property called attribtue 

### Syntax
```
<abbr attribute="value">short text here </abbr>
```

#### Sample code for abbr
```
<abb title="Javascript">js</abbr>
```

# bdo
1. it is used to display text rtl(right to left) or ltr (left to right)
2. pair tag
3. rtl to display text in right to left
4. ltr to display text in left to right

### Syntax

```
<bdo dir="rtl"> your text here </bdo>
```
#### Sample Code for bdo 
```
<bdo dir="rtl">HI</bdo>
```

# i
1. it is used to display text in italic
2. it is pair tag

### Syntax
```
<i> your text here </i>
```

#### Sample Code for **i**

```
<i>Hi</i>
```

# b
1. it is used to disply text in bold
2. it is pair tag

### Syntax
```
<b> your text here </b>
```
#### Sample Code for **b**

```
<b>Hello World </b>
```

# anchore Tag (a)
1. it is used to create hyper link when the user click on the hyper link it rediect to that link specific web page.
2. it is pair tag
3. **href** it is a attribute, used to put any hyper link.
4. **target** it is used to open the web pag in sparate window.(_blank)

```
Attributs

1. href 
2. target 

```

### Syntax 

```
<a href="target url here" target="_blank">Link text here </a>
```

#### Sample Code for **a**

```
<a href="https://www.google.com/" target="_blank">Google </a>
```

# List Tags
1. ul - unordered list (.)
2. ol - ordered list (1,2,3)

**UL**
1. ul stands for unordered list
2. it is used to display list items with bullets
3. ul inside li list items

### Syntax
```
<ul>
    <li>Your ITEM</li>
     <li>Your ITEM</li>
 </ul>
 ```

#### Sample Code for **UL**
```
<ul>
    <li>HTML</li>
     <li>CSS</li>
 </ul>
 ```


**OL**
1. ol stands for ordered list
2. it is used to display list items with number
3. ol inside li list items

### Syntax
```
<ol>
    <li>Your ITEM</li>
     <li>Your ITEM</li>
 </ol>
 ```

#### Sample Code for **UL**
```
<ol>
    <li>HTML</li>
     <li>CSS</li>
 </ol>
 ```

 **DL**
1. dl stands for defination list
2. it is used to display collection defination
3. dl inside dt (defination titile)
4. dl inside dd(data defination) 

### Syntax
```
<dl>
    <dt>Your ITEM</dt>
    <dd>Your ITEM</dd>
    <dt>Your ITEM</dt>
    <dd>Your ITEM</dd>
 </dl>
 ```

#### Sample Code for **DL**
```
<dl>
    <dt>HTML</dt>
    <dd>used display static webpage on browser</dd>
    <dt>CSS</dt>
    <dd>used to display color</dd>
 </dl>
 ```

 # Table Tags
 1. Table used to display data in structre way 
 2. table is a collection  of rows. each row is a collection of cell 
 3. table is represented a table contains "tr"(row ) "td"(cell) table heading "th" caption 
 ## Tags Used in Table 
 ```
 <table></table>
  <thead><thead>
  <th><th>
 <caption></caption>
 <tr><tr>
 <td></td>
 ```

1. tr stands for **Table row**
2. th stand for **Table Header**
3. td stands for **Table data**
4. Caption tag is used to specficy of titile for the table 
5. attribut 
 1. border -we need give the number ex:-1,2,3 ....
 2. rowspan 
    1. "n"  specify the no of row to merge
 3. colspan
    1. "n" specify the no of cell to merge
## Syntax
```
<table>
    <tr>
    <th>Your Header</th>
    <th>Your Header</th>
    <th>Your Header</th>
    </tr>
    <tr>
    <td>Your Text here</td>
    <td>Your Text here</td>
    <td>Your Text here</td>
    </tr>
</table>
```
# Form
1. it is parent tag
2. **input** tag is ued for create a user or form control

# input 
1. input unpair tag

## syntax
```
<form>
<input type="text" />
</form>
```
### Sample code for **input**
```
<form>
    Name:<input type="text" />
</form>
```

### Attributes for Input
```
1. type
    ->Text :- Crate textbox.Textbox is ued to accept string value from user.
    ->Number :- Used to enter number from user. 
    ->Password :- Create Password textbox.
    -> Button :- Create button from inupt used to javascript event 
    -> Checkbox :- Create checkboxs used to display Yes/No of option to the user.
    -> Radio :- Create radio button used to display yes/no question.
    -> hidden :- Crate hidden value or file
    -> submit :- Create submit form, submit is ued to submit the form to the server page
    -> file :- to upload file or image in server
    -> Search :- To display seach box in web page
    -> image :- 
 ``` 

