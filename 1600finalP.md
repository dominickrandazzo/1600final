# Markdown Tutorial

To follow along and test out what is demonstrated in this tutorial I recommend you use this website [here (click me!)](https://markdown-it.github.io/)  
Make sure that you check the box at the top that says _html_ so that parts of this tutorial will work correctly.

If you would like a downloadable software that you can use offline, I personally use Microsoft Visual Studio. It is free and supports many different languages besides just Markdown. [Here is the link to download Visual Studio.](https://visualstudio.microsoft.com/downloads/)

---

## Headers

Headers are a way to clarify what a section will be about or to give a word or sentences some signifigance. Like the header I included above, it exclaimed that this current section is all about headers.

Headers are declared by putting # at the beginning of a line. The size of your header depends on how many hashtags you use. There are 6 different sizes you can use so it can look like # or ## all the way to ######. Here is the syntax for how to format headers.

```# One hashtag for header 1```   
```###### All the way up to 6```

Now here is what all six look like.

# This is the first header, the biggest one.
## This is the second header.
### This is the third header.
#### This is the fourth header.
##### This is the fifth header.
###### This is the sixth header, the smallest one. Smaller than regular text infact.

Additionally for the first and second header, you can use = and - respectively on the line below your header text. The following is how the syntax looks for these two headers.

```The first header```   
```=```

```The second header```   
```-```

Now here is the first in action
=

Along with the second
-

---

## Emphasis

You can add some flavor to your text by putting emphasis in your sentences.
  
By putting one *  or _ before and after a word you can make it italic. Like *this*.
 
By putting two * or _ before and after a word you can make it bold. Such as **this**.

Finally by putting two ~ before and after a word you can make a word strikethrough. Did you know that symbol is called ~~a tild~~ ~~a tiled~~ a tilde?

Bonus emphasis: By only using one ~ before and after you can make individual words ~shrink~ and shift ~down~. This can only be used on individual words and not multiple words.

You can also do a combination of italic and bold by using a combination of * and _. In a sentence you can take it even further, lets say you want to make the first three words bold but only the third word bold and italic. The syntax would look like this.  
```**first second *third***```  

If you wanted the first three words to be italic but only the third to be bold it would look like this.  
```_First second __third___```

**In *practice* it could *look like* this!**  
*Or it could **be mixed** like this.*


---

## Lists

Lists are the main way that you can add in numbered items and bullet points. Very useful to organize information.
**Unordered** lists is the version that looks like bullet points. They start by inserting a + or - or * at the beginning of a line, followed by a space, then whatever you enter. More bullet points can be added by entering to the next line and using the symbols listed.

```+ This```  
```+ Is```  
```+ The```  
```+ Syntax```  

+ This
+ Is
+ What
+ Ordered lists look like

You can add sublists within lists by using two spaces before the symbol. For every further sublist just add two more spaces.

+ This
  + Is
    + A
      + Sublist

There are also numbered lists if you don't want bullet points. You start these lists by inserting a 1. at the beginning of the sentence. Any further numbered lines can be marked by following in order like 2. 3. 4. or you can just keep using 1. over again.

```1. This```  
```2. Is```  
```2. The```  
```3. Syntax```  

1. This
2. Is
2. What
3. Numbered lists look like.

---

## Links

You can create links that are attached to text, headers, almost everything.
There are two main ways to create links. There are direct inline links and reference links.

This is the inline links syntax.

```[This is the text you click](www.thewebsite.com)```

And here it is in action.

[This should take you to youtube.](https://www.youtube.com/)

Reference links work very similar. Instead of having the text go right to the link, it directs to a seperate reference that in turn directs to a link. This is useful if you are planning on creating links en masse that direct to the same website, that way you will end up not having to enter the entire url everytime. The reference links do not have to appear immediately afterwards. As long as it is in the document it will work.

This is the reference link syntax.

```[This is the text you click](reference)```  
```[reference]: https://www.youtube.com/ ```

This is the reference link in action.

[This is the text you click](reference)  
[reference]: https://www.youtube.com/

---

## Images

Images are very similar to how links are formatted. The two main differences are that you insert an exclamation point at the beginning and instead of turning text into a link, you attach descriptive text to the picture that idealy describes the picture.

This is the inline link syntax.

``` ![image descriptive text](www.thepictureurl.com)```

And here it is in action.

![This is a cute dog](https://www.opkansas.org/wp-content/uploads/2021/03/pit-bull-dog-web.jpg)

For image references, the only difference is that instead of using parentheses () you use brackets [] to signal the reference.

This is the reference link syntax.

```![image descriptive text][reference]```

```[reference]: www.theimageurl.com)```

And here it is in action.

![This is a cute dog][pitbull]

[pitbull]: https://www.opkansas.org/wp-content/uploads/2021/03/pit-bull-dog-web.jpg

---

## Highlighting

You can highlight sections of text by using a back-tick before and after the text. This will make it stand out.

Here is the syntax for text highlighting.

##### The second half `is highlighted .`

Highlighting code applies the color coding that coding languages use within markdown. Markdown doesn't innately support code highlighting; however, most of the programs that run markdown, such as GitHub, does support code highlighting. The render program you use also haas to support the language that you are trying to highlight. I will be using javascript and python in this example as GitHub supports those.  
Highlighted lines of code are started by using three back-ticks ```, you then signify the language you are using immediatly after the back-ticks, and finally you signal the end of the highlighting by also using three back-ticks ``` at the end.

This is what the syntax looks like for highlighting code, minus the period after the first back-tick in the examples.

##### ```javascript  
##### var s = "Notice the var and this text are different colors.";
##### alert(s);
##### ```
 
##### ```python
##### s = "Notice the print and this text are different colors."
##### print s
##### ```

This is what is what highlighting looks like in action.

```javascript
var s = "Notice the var and this text are different colors.";
alert(s);
```
 
```python
s = "Notice the print and this text are different colors."
print s
```
 
```
You can't tell from viewing this is in a renderer, but this whole block of text is using the highlighting syntax.
Nothing is being highlighted here because there is no coding language recognized.
```

---

## Tables

Markdown itself does not support the ability to create tables. Just like highlighting, renders that use versions of markdown with extensions allow for tables. GitHub allows the implementation of tables.

Tables have the most unique syntax out of anything we have covered so far. I feel it would be easier to show the syntax and then explain the rules behind what is happening.

```
| Table | Like | This |
| --- | :---: | ---: |
| Left | Middle | Right |
```
Lets dissect what is happening here. Each column is created by entering in this slash | then the title of the column followed by another slash |. The next line will look the same except it should contain three dashes --- with a colon either after the last dash or before and after the last dash. This formats for how the column is aligned. Just three dashes --- is left aligned, a colon then three dashes ending with a colon :---: center aligns the column, and finally three dashes ending in a colon ---: right aligns the column. Every new line after that extends the column down by one for more information. You create additional rows by entering your text followed by a slash |. Every additional row has to have the alignment column beneath it once and it can be different from other rows. The dash | ending each line is optional but I recommend inserting it regardless so it looks nicer and will be less susceptible to errors. You can include headers for an entire line row by entering the # at the start of the line but that can get very messy very quickly. Finally adding emphasis and highlighting is allowed and won't mess up how the tables look like headers can.

Here is what tables look like in action.

| This | Is | A | Table |
| --- | --- | ---: | :---: |
| Left | Left | Right | Center |
| *Italic* | **Bold** | ~Strikethrough~ | `Highlighted` |

---

## Blockquotes

Blockquotes are typically used to signify text like email or sms, direct quotes, or text out of a book.  
You start blockquotes in a similar way to headers. Instead of hashtags you use one > greater than symbol at the start of the line.

Blockquote syntax

```
> This is how you create a blockquote,
```

This is what blockquotes look like in action.

> This is how you create a blockquote.

Blockquotes can be nested within each other by inserting an extra greater than sign > for each new nested line.

Here is the nested blockquote syntax

```
> This is the first line
>> The second line
>>> The third line
```

Here is nested blockquotes in action

> This is the first line
>> The second line
>>> The third line

---

## Inline HTML

You can also include HTML in your markdown if your render allows for html.

I won't go over the syntax since this isn't a HTML tutorial but I will show you what the final product looks like.

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

---

## Horizontal Rules

Horizontal rules are the long lines I have been using the seperate the different sections in this tutorial. They are very easy to incorporate. On an empty line you just instert three either asterisks, hyphens, or underscores.

This is the syntax for all horizontal rules.

```
---
or
___
or
***
```

This is what they look like in the same order. (Hint they all look the same)

---
___
***

---

## Line Breaks

Line breaks are how you seperate out your lines of text in markdown. There are two ways to do this. A hard line break is when you enter in an empty line inbetween text. This breaks text apart like a paragraph. A soft break occurs when you enter two spaces at the end of your line. This makes the next line directly following appear below the line like a trailing sentence.

I can't show the syntax for obvious reasons but what I did for this sentence was a hard break.
And this sentence used a soft break.

---

## Videos

This is mainly useful for Youtube videos. This uses the href command from HTML which since that isn't markdown specific I will not explain the syntax. This is to merely show you can do this is the render allows for href.

<a href="https://www.youtube.com/watch?v=nxoe5DjDd74" target="_blank"><img src="https://i.ytimg.com/vi/nxoe5DjDd74/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDEum97JaeRLRqpMF-X7sNnXVOjhA" 
alt="Fonky Monky Friday" width="300" height="300" border="30" /></a>
