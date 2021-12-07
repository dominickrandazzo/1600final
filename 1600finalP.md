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

[This should take you to youtube.](www.youtube.com)

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

---

## Blockquotes

---

## Inline HTML

---

## Horizontal Rules

---

## Line Breaks

---

## Videos

