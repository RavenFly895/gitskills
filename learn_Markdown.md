# Learn Markdown

## Basic Syntax

### Headings
just using different numbers of '#' to denote different ranks of Headings.

### Paragraphs:
using the 'space line' to denote different paragraphs

### Changing lines:
add two 'space' and one 'enter' at the end of one sentence.  
This is called 'trailing whitespace'.


But it is found that 'space' is not easily found at the end of one sentence.  
So another effective way to implement is adding <br> at the end

### highlighting keywords
#### bold or light
Adding double asterisks, which is *. <br>
This can achieve **bold** font weight. We also can achieve it inside a phrase, like **angela**smith.

#### Italic
Adding only one asterisks to achieve.
For example, I really like *italic* writing skills. <br>
Besides, using * inside a word has the same effect as before.

#### Bold & Italic
adding Three * to achieve both.<br>
I really like the ***italic*** writing skills.

### Quoting 
To create a **Quote Block**, an '>' can be used, like below, <br> note that it must begin a new line. 
> Dorothy followed her through many of the beautiful rooms in her castle.

In one block, multiple paragraphs can be realized like:
> I am very happy to learn it today.
>
> Why don't we use it, if so convenient.

If I want to try embedded quotation, things come like this: <br>
> Today I feel a little uncomfortable about my chest muscle
> > But I don't think it is any kind of heart disease, since the symptom is really like the muscle starin. 
 
So if multiple indention is needed, just add the >

If I want to add some elements in the quotation, I can do this: <br>
> - I can assign one item to this sentence.
> - It just makes me feel excited.
> I *really* like to try something **different**.

### List
#### List with orders 
content has to be started with **a number and an English** .<br>
like this:<br>
1. first term
2. second term
3. Third term
4. Fourth term

#### List without orders
Sentences starting with symbols like, *,-,+;<br> 
YOU should pick **one delimeter** and *stick to it* <br> 
with indented item can have the embedded list.<br>
- First term
  - First term and a point.
- Second term
  - Second term and a point
    - fds 
    - fdas
  
if more elements are included in one list: <br>
that element has to be started with **four spaces or a 'Tab'**.
- First term
  - second term
    
    A long time ago, a boy was born with the magic
- Third term <br>
    So, from the syntax, you can see the key is to keep them with the corresponding indent.

- A new thing
    > I want to quote something different
- The last thing 

1. open the file 
2. find the following code block on line 21
        <html>
            <head>
4. update the title to match 



1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.

### Code display
using the inverse quotation , which is below the `esc`, to make a word or phrase look like a code format.<br>
change the meaning of that quotation, <br>

``I want to try to restore the effect `apple`.``
with double quotation marks, the single one can be included.

code block just using two tabs to indent the sentences <br>

    This is a python code: Hello world!

### Horizontal Rule
To create a horizontal Rule, three - or * or _ in a row can be used. <br>
Best practice:<br>
Considering the compatability, blank lines should be added both forward and behind.

Try to put a blank line before and after the Horizontal line

---

beginning new text.

### Hyperlink
This is a link [Link's name: Baidu](https://baidu.com "title shown when the mouse stops on the name").

with <> can convert the email or web address to a real link.<br>
<wangh466@mcmaster.ca>
The hyperlink can be comnbined with highlighting syntax, like this: ***[Baidu](https://baidu.com "百度")***

or combined with inverse quotation like [`Baidu`](https://baidu.com "百度")

#### type of quotation
For hyperlinks connecting the content inside a document. <br>
[hobbit-hole] [1] <br>
[rabbit-hole] [2]

For quotating some literature or URL <br>
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'hobbit lifestyles'

If there is a space in the URL, subsitute the space with %20 <br>
[link](https://www.example.com/my%20great%20page 'example')

### Inserting an Image
similar to the hyperlink <br>
For the image, exclaimation mark is needed.
![A beautiful image](./A_boy.jpg 'I like this picture') <br>
"a beautiful image" is used to supplement information when the image is invisable.<br>
the Image must be in the relative path rather than the absolute path<br>

besides, hyperlink can also be assigned to one picture. Just combine the knowledge learned before. <br>
[![A girl I appreciate](./A_girl.jpg 'This one I also like')](https://github.com/RavenFly895/gitskills)

### Escape Characters (转义字符)
That is, the backflash \ <br>
* A listed item <br>
  
\* Just a comparison 

4 < 5\

    fdsa 
    **fsda** 

    This is a regular paragraph.

    <table>
        <tr>
            <td>Foo</td>
        </tr>
    </table>

    This is another regular paragraph.













