1) What is HTML?

HTML is short for HyperText Markup Language and is the language of the World Wide Web. It is the standard text formatting language used for creating and displaying pages on the Web. HTML documents are made up of two things: the content and the tags that format it for proper display on pages.


2) What are tags?

Content is placed in between HTML tags in order to properly format it. It makes use of the less than symbol (<) and the greater than symbol (>). A slash symbol is also used as a closing tag. For example:

<strong>sample</strong>
1
<strong>sample</strong>
 

3) Do all HTML tags come in a pair?

No, there are single HTML tags that do not need a closing tag. Examples are the <img> tag and <br> tags.

4) What are some of the common lists that can be used when designing a page?

You can insert any or a combination of the following list types:
– ordered list
– unordered list
– definition list
– menu list
– directory list
Each of this list types makes use of a different tag set to compose

5) How do you insert a comment in HTML?

html interview Questions

Comments in HTML begins with “<!–“nd ends with “–>”. For example:

<!-- A SAMPLE COMMENT -->
1
<!-- A SAMPLE COMMENT -->
 


6) Do all character entities display properly on all systems?

No, there are some character entities that cannot be displayed when the operating system that the browser is running on does not support the characters. When that happens, these characters are displayed as boxes.

7) What is an image map?

Image map lets you link to many different web pages using a single image. You can define shapes in images that you want to make part of an image mapping.

8 ) What is the advantage of collapsing white space?

White spaces are a blank sequence of space characters, which is treated as a single space character in HTML. Because the browser collapses multiple spaces into a single space, you can indent lines of text without worrying about multiple spaces. This enables you to organize the HTML code into a much more readable format.

9) Can attribute values be set to anything or are there specific values that they accept?

Some attribute values can be set to only predefined values. Other attributes can accept any numerical value that represents the number of pixels for a size.

10) How do you insert a copyright symbol on a browser page?

To insert the copyright symbol, you need to type &copy; or & #169; in an HTML file.

11) How do you create links to sections within the same page?

Links can be created using the <a> tag, with referencing through the use of the number (#) symbol. For example, you can have one line as <a href=”#topmost”>BACK TO TOP</a>, which would result in the words “BACK TO TOP” appearing on the webpage and links to a bookmark named topmost. You then create a separate tag command like <a name=”topmost”> somewhere on the top of the same webpage so that the user will be linked to that spot when he clicked on “BACK TO TOP”.

12) Is there any way to keep list elements straight in an HTML file?

By using indents, you can keep the list elements straight. If you indent each subnested list in further than the parent list that contains it, you can at a glance determine the various lists and the elements that it contains.

13) If you see a web address on a magazine, to which web page does it point?

Every web page on the web can have a separate web address. Most of these addresses are relative to the top-most web page. The published web address that appears within magazines typically points this top-most page. From this top level page, you can access all other pages within the website.

14) What is the use of alternative text in image mapping?

When you use image maps, it can easily become confusing and difficult to determine which hotspots correspond to which links. Using alternative text lets, you put a descriptive text on each hotspot link.

15) Do older HTML files work on newer browsers?

Yes, older HTML files are compliant to the HTML standard. Most older files work on the newer browsers, though some features may not work.

16) Does a hyperlink apply to text only?

No, hyperlinks can be used in the text as well as images. That means you can convert an image into a link that will allow users to link to another page when clicked. Surround the image within the <a href=” “>…</a> tag combinations.

17) If the user’s operating system does not support the needed character, how can the symbol be represented?
17) Если операционная система пользователя не поддерживает необходимый символ, как символ может быть представлен?

In cases wherein their operating system does not support a particular character, it is still possible to display that character by showing it as an image instead.
В случаях, когда их операционная система не поддерживает определенный символ, все еще возможно отобразить этот символ, показав его вместо изображения.

18) How do you change the number type in the middle of a list?
18) Как вы меняете тип номера в середине списка?

The <li> tag includes two attributes – type and value. The type attribute can be used to change the numbering type for any list item. The value attribute can change the number index.
 Тег <li> включает в себя два атрибута - тип и значение. Атрибут type можно использовать для изменения типа нумерации для любого элемента списка. Атрибут значения может изменить числовой индекс.
  <a href="http://html5doctor.com/ol-element-attributes/">Article about Attributes: type, start, value, and reversed</a>
  Example:
  <!--
  <ol>
<li value="30"> makes this list item number 30.
<li value="40"> makes this list item number 40.
<li> makes this list item number 41.
</ol>
  -->
  We can specify the list’s style using the type attribute, with the following values:

type attribute values and their corresponding list counter types

ol type="" values	| Equivalent list-style-type
------------------|-----------------------------
type="1" |	decimal (default style)
type="a"	| lower-alpha
type="A"	| upper-alpha
type="i"	| lower-roman
type="I"	| upper-roman

19) What are style sheets?

Style sheets enable you to build consistent, transportable, and well-defined style templates. These templates can be linked to several different web pages, making it easy to maintain and change the look and feel of all the web pages within site.

20) State  bullet types available in HTML 
Что такое таблицы стилей?

With ordered lists, you can select to use some different list types including alphabetical and Roman numerals. The type attribute for unordered lists can be set to disc, square, or circle.
С упорядоченными списками вы можете выбрать использование нескольких различных типов списков, включая алфавитные и римские цифры. Атрибут типа для неупорядоченных списков может быть установлен на диск, квадрат или кружок.
<a href="https://www.w3schools.com/html/html_lists.asp">HTML Lists</a>

21) How do you create multicolored text in a webpage?
Как вы создаете многоцветный текст на веб-странице?

<a href="https://www.w3schools.com/tags/att_font_color.asp">Example</a>

To create text with different colors, use the <font color=”color”>…</font> tags for every character that you want to apply color. You can use this tag combination as many times as needed, surrounding a single character or an entire word.

Чтобы создать текст с разными цветами, используйте теги <font color = ”color”>… </ font> для каждого символа, к которому вы хотите применить цвет. Вы можете использовать эту комбинацию тегов столько раз, сколько необходимо, окружая один символ или целое слово.

22) Why are there both numerical and named character entity values?
Почему существуют числовые и именованные значения сущностей символов?

<a href="https://www.w3schools.com/charsets/ref_html_ascii.asp">Explaining</a>
<a href="https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references">List of XML and HTML character entity references</a>
The numerical values are taken from the ASCII values for the various characters, but these can be difficult to remember. Because of this, named character entity values were created to make it easier for web page designers to use.

Числовые значения взяты из значений ASCII для различных символов, но их может быть трудно запомнить. Из-за этого были созданы значения именованных символьных сущностей для облегчения использования дизайнерами веб-страниц.

23) Write an HTML table tag sequence that outputs the following:
50 pcs 100 500
10 pcs 5 50

Answer:

<table> 
<tr> 
<td>50 pcs</td> 
<td>100</td> 
<td>500</td> 
</tr> 
<tr> 
<td>10 pcs</td> 
<td>5</td> 
<td>50</td> 
</tr> 
</table>
1
2
3
4
5
6
7
8
9
10
11
12
<table> 
<tr> 
<td>50 pcs</td> 
<td>100</td> 
<td>500</td> 
</tr> 
<tr> 
<td>10 pcs</td> 
<td>5</td> 
<td>50</td> 
</tr> 
</table>
24) What is the advantage of grouping several checkboxes together?

Although checkboxes don’t affect one another, grouping checkboxes together help to organize them. Checkbox buttons can have their name and do not need to belong to a group. A single web page can have many different groups of checkboxes.

25) What will happen if you overlap sets of tags?

If two sets of HTML tags are overlapped, only the first tag will be recognized. You will find this problem when the text does not display properly on the browser screen.

26) What are applets?

Applets are small programs that can be embedded within web pages to perform some specific functionality, such as computations, animations, and information processing. Applets are written using the Java language.

27) What if there is no text between the tags or if a text was omitted by mistake? Will it affect the display of the HTML file?

If there is no text between the tags, then there is nothing to format. Therefore no formatting will appear. Some tags, especially tags without a closing tag like the <img> tag, do not require any text between them.

28) Is it possible to set specific colors for table borders?

You can specify a border color using style sheets, but the colors for a table that does not use style sheets will be the same as the text color.

29) How do you create a link that will connect to another web page when clicked?

To create hyperlinks, or links that connect to another web page, use the href tag. The general format for this is: <a href=”site”>text</a>
Replace “site” with the actual page URL that is supposed to be linked to when the text is clicked.

30) What other ways can be used to align images and wrap text?

Tables can be used to position text and images. Another useful way to wrap text around an image is to use style sheets.

31) Can a single text link point to two different web pages?

No. The <a> tag can accept only a single href attribute, and it can point to only a single web page.

32) What is the difference between the directory and menu lists and the unordered list?


The key difference is that the directory and menu lists do not include attributes for changing the bullet style.

33) Can you change the color of bullets?

The bullet color is always the same as that of the first character in the list item. If you surround the <li> and the first character with a set of <font> tags with the color attribute set, the bullet color, and the first character will be a different color from the text.

34) What are the limits of the text field size?

The default size for a text field is around 13 characters. However, if you include the size attribute, you can set the size value to be as low as 1. The maximum size value will be determined by the browser width. If the size attribute is set to 0, the size will be set to the default size of 13 characters.

35) Do <th> tags always need to come at the start of a row or column?

Any <tr> tag can be changed to a <th> tag. This causes the text contained within the <th> tag to be displayed as bold in the browser. Although <th> tags are mainly used for headings, they do not need to be used exclusively for headings.

36) What is the relationship between the border and rule attributes?

Default cell borders, with a thickness of 1 pixel, are automatically added between cells if the border attribute is set to a nonzero value. Likewise, If the border attribute is not included, a default 1-pixel border appears if the rules attribute is added to the <table> tag.

37) What is a marquee?

A marquee allows you to put a scrolling text in a web page. To do this, place whatever text you want to appear scrolling within the <marquee> and </marquee> tags.

38) How do you create text on a webpage that will allow you to send an email when clicked?

To change text into a clickable link to send email, use the mailto command within the href tag. The format is as follows:

<A HREF=”mailto:youremailaddress”>text to be clicked</A>
1
<A HREF=”mailto:youremailaddress”>text to be clicked</A>
 

39) Are <br> tags the only way to separate sections of text?

No. The <br> tag is only one way to separate lines of text. Other tags, like the <p> tag and <blockquote> tag, also separate sections of text.

40) Are there instances where the text will appear outside of the browser?

By default, the text is wrapped to appear within the browser window. However, if the text is part of a table cell with a defined width, the text could extend beyond the browser window.

41) How are active links different from normal links?

The default color for normal and active links is blue. Some browsers recognize an active link when the mouse cursor is placed over that link; others recognize active links when the link has the focus. Those that don’t have a mouse cursor over that link is considered a normal link.

42) Do style sheets limit the number of new style definitions that can be included within the brackets?

Style sheets do not limit the number of style definitions that can be included within the brackets for a given selector. Every new style definition, however, must be separated from the others by a semicolon symbol.

43) Can I specify fractional weight values such as 670 or 973 for font weight?

Implementation largely depends on the browser, but the standard does not support fractional weight values. Acceptable values must end with two zeroes.

44) What is the hierarchy that is being followed when it comes to style sheets?

If a single selector includes three different style definitions, the definition that is closest to the actual tag takes precedence. Inline style takes priority over embedded style sheets, which takes priority over external style sheets.

45) Can several selectors with class names be grouped together?

You can define several selectors with the same style definition by separating them with commas. This same technique also works for selectors with class names.

46) What happens if you open the external CSS file in a browser?

When you try to open the external CSS file in a browser, the browser cannot open the file, because the file has a different extension. The only way to use an external CSS file is to reference it using <link/> tag within another HTML document.

47) How do you make a picture into a background image of a web page?

To do this, place a tag code after the </head> tag as follows:

<body background = “image.gif”>
1
<body background = “image.gif”>
Replace image.gif with the name of your image file. This will take the picture and make it the background image of your web page.

48) What happens if the list-style-type property is used on a non-list element like a paragraph?

If the list-style-type property is used on a non-list element like a paragraph, the property will be ignored and do not affect the paragraph.

49) When is it appropriate to use frames?

Frames can make navigating a site much easier. If the main links to the site are located in a frame that appears at the top or along the edge of the browser, the content for those links can be displayed in the remainder of the browser window.

50) What happens if the number of values in the rows or cols attribute doesn’t add up to 100 percent?

The browser sizes the frames relative to the total sum of the values. If the cols attribute is set to 100%, 200% the browser displays two vertical frames with the second being twice as big as the first.

51) Which browsers support HTML5?

The latest versions of Google Chrome, Apple Safari, Mozilla Firefox, and Opera all support most of the HTML5 features.

52) Name two new tags included in the HTML 5

<Video> and <Audio> are new tags which are included in HTML5 version. They are mainly used as a replacement for Flash, Silverlight, and similar technologies to play multimedia items.

53) Do you know which are two semantic tags are included in HTML5 version?

The <article> and <section> tags are two new tags that are included in HTML5. Articles can be composed of multiple sections that can have multiple articles. An article tag represents a full block of content which is a section of a bigger whole.

54) What is <figure> in HTML5?

This tag represents a piece of self-contained flow content. It is mostly used as a single unit as a reference the main flow of the document.

55) What is the use of Canvas element?

The canvas element helps to build charts, graphs, bypass Photoshop to create 2D images and place them directly into HTML5 code.

56) What are the new FORM elements which are available in HTML5?

The new Form elements in HTML5 offers much better functionality than the earlier versions.

The tags given provided to carry out these functions are:

1) <datalist> – This tag is use to specify a list of options for input controls.

2) <keygen> – This tag represents a key-pair generator field.

3) <output> – It represents the result of any scripting calculation.

57) Tell me two benefits of HTML5 Web Storage
Two main benefits of HTML5 Web Storage:

It can store up to 10 MB data which is certainly more than what cookies have.
Web storage data cannot be transferred with the HTTP request. It helps to increase the performance of the application.
58) What are two types of Web Storage in HTML5?

Two storage types of HTML5 are:

Session Storage:

It stores data of current session only. It means that the data stored in session storage clear automatically when the browser is closed.

Local Storage:

Local storage is another type of HTML5 Web Storage. In local storage, data is not deleted automatically when the current browser window is closed.

59) What is the Application Cache in HTML5 and why it is used?

The Application Cache concept means that a web application is cached. It can be accessible without the need for internet connection.

Some advantages of Application Cache:

Offline browsing – Web users can also use the application when they are offline.
Speed – Cached resources load quicker
Reduce the server load – The web browser will only download updated resources from the server.
60) Explain five new input types provided by HTML5 for forms?

Following are the important, new data types offered by HTML5:

Date: It allows the user to select a date.
datetime-local: This input type allows the user to select a date and time without time zone.
datetime: This input type allows the user to select a date and time with time zone.
month: It enables the user to select a month and year
email: These input fields used to contain an e-mail address.
