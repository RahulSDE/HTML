## **WHAT IS HTML**
- `HTML` stands for **HYPER TEXT MARKUP LANGUAGE**.
    - `Hyper-Text` : A special type of text document in which you can put hyperlink of another text document.
    - `Markup Language` : Text-encoding system which specifies the structure and formatting of a document.
- `HTML` - not a programming language. Anything to be called as a programming language must support the decision making (if, else etc.) which HTML doesn't support.
- `HTML` provides the skeleton of a webpage.
- Example of Markup language - **HTML, Markdown**.
- The basic building blocks of **HTML** is `Tags`.

## **TAGS**
- a single mechanism using which you can tell what is this part of document actually meaning. 
- **Syntax:**
    ```
        <tag name> some information </tagname>
           |                            |
        opening tag                    closing tag
    ```
- With a tag, there is an opening and closing tag associated with it.
- There is an exception. There are some tags which are self-closing tags means we don't need to put closing tag with them.
    - ex:
    ``` 
        <tagname>
             |
        Here opening and closing is managed by same tag
    ```

### **DIFFERENT TYPES OF TAGS**

#### **1) HEADING TAGS**
- 
    ```
        <h1> this is heading 1 </h1>
        <h2> this is heading 1 </h2>
        <h3> this is heading 1 </h3>
        <h4> this is heading 1 </h4>
    ```
- Used to put heading in the docs which is in bold colour.

#### **2) PARAGRAPHS TAGS**
- 
    ```
        <p> this is paragraph </p>
    ```
- Used for paragraphs.
- The text will be in normal colour.

#### **3) LIST TAGS**
- There are two types of list tags.
    ```
              List in HTML 
                  |
        -------------------------
        |                        |
    unordered                  ordered
    . list item 1             1. list item1
    . list item 2             2. list item2
    . list item 3             3. list item3
    . list item 4             4. list item4
    SYNTAX:                  SYNTAX:
        <ul>                   <ol>
         <li>item1</li>           <li>item1</li>
         <li>item2</li>           <li>item2</li>
         <li>item3</li>           <li>item3</li>
        </ul>                  </ol>
    ```
- Used to put heading in the docs which is in bold colour.

#### **4) IMAGE TAGS**
-  Syntax:
    ```
        <img src= " " alt= " "/>
    ```
- Image tag is a self-closing tag.
- There are many attributes associated with this tag to show characterstics of image.
- `src = " " `  : Here in the inverted comma, we write the path/ address of image where it is actually present.
- `alt = " " `  : Here we write the description of image, which screen reader will read for blind people.

``` 
Inline tag                               Block tag
   |                                          |
a tag which always put the              a tag which always put
info of next tag in the                 the info of next tag 
same line.                               int the new line. 
```
#### **5) DIV TAGS**
- Syntax
    ```
        <div>
            one divtag
        </div>
        <div>
            hi there
            <img src=" " alt=" "/>
        </div>
    ```
- used to write the general statement mix with anything.
- It is an block tag.

#### **6) SPAN TAGS**
- Syntax
    ```
        <span> There is span1 </span>
        <span> There is span2 </span>
    ```
- used to write the general statement mix with anything in the same line..
- It is an inline tag.

#### **7) AUDIO AND VIDEO TAGS**
#### **8) MARQUEE TAGS**
- webpage me line ko ek taraf se dusre taraf i.e. moving line create karne ke liye use hota hai.
- Syntax:
    ```
    <marquee behaviour = "scroll" direction = "right"> TEXT </marquee>
    ```
    


