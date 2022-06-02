# Udemy Angela Yu's Web Developer Class
This is a practice of Angela Yu's Full-Stack Web Developer class

<h2>Learning Summary</h2>
  <h3>Section 2: Intro to HTML</h3>
    <ul>
      <li>Boilerplate: in Atom editor, type html and hit Enter</li>
      <li>List: ul(unordered list), ol(ordered list), li(list item)</li>
      <li>Image</li>
      <li>Hypterlink</li>
    </ul>

<h3>Section 3: Intermediate HTML</h3>
  <ul>
    <li><strong>Table</strong></li>
      <ul>
        <li>tr:table row, td:table data</li>
        <li>thead: table head, tbody: table body , tfoot: table foot</li>
          <ul>Keeping headers in thead sections helps formatting the table. For example, if we want to froze the header when scroll down the table, we can do that by calling thead.</ul>
        <li>inside table head: th: table head element in cell
      </ul>
    <li><strong>Use table to layout elements</strong></li>
      <ul>
        <li>cellspacing = "20": add space between cells</li>
      </ul>
    <li><strong>The action of the form</strong></li>
      <ul>  
        <li>
          &lt;form class="" action="index.html" method="post"&gt;
        </li>
          <ul>If there's a submit button in the form, clicking the submit button will derive back to the index.html page, which is defined by the action value of the form.
          </ul>
        <li>&lt;form class="" action="mailto: wangyw@email.arizona.edu" method="post"&gt;
        </li>    
      </ul>
    <li><strong>Escaping angle brackets</strong></li>
      <ul><li>use "&amp;lt;" and "&amp;gt;" to replace "<" and ">".
      </ul>
    <li><strong>Encoding type</strong></li>
      <ul>
        <li>&lt;form action="mailto: wangyw@email.arizona.edu" method="post" enctype = "text/plain"&gt;</li>
      </ul>
</ul>

<h3>Section 4: Introduction to CSS</h3>
  <p>Priorities to use CSS: inline(in body) > internal(in head) > external(in css files)</p>
  <ul>
    <li><strong>Google browser default CSS documentation</strong></li>
    <li><strong>Add CSS file and add link to the header of the index.html</strong></li>
    <li><strong>Basic grammar: selecter { property: value; }</strong></li>
      <ul>
        <li>Where to find the properties of the selecters? https://developer.mozilla.org/en-US/docs/Web/CSS/Reference</li>
      </ul>
    <li><strong>class vs id</strong></li>
      <ul>
        <li>class:
        <ul>
        <li>class = "classname1 classname2"   
        <li>.classname1{}   .classname2{};
      </ul>
        <li>id: #id{}</li>
        <li> class and id selecters are more specific than general selecters, so that it can specify a property of an id element despite the general selecter. e.g. h1 background color</li>
        <li>Difference:We can have repeated class names but can only have unique id names. So class can be used to group elements.
        </li>
      </ul>
    <li><strong>:pseudo classes</strong></li>
      <ul>
        <li>image:hover{background-color: gold;}
      </ul>
  </ul>
<h3>Section 5: Intermediate CSS: display, positioning</h3>
  <ul>
  <li><strong>Inline display elements</strong>: &lt;span&gt;some elements&lt;/span&gt;</li>
  <li>Other inline display elements: img, a
  <li>We can <strong>change a box display elements to inline display elements</strong>. For example, &lt;p&gt;is a box display element, by adding a property display:inline, it turns into an inline display element. The same for inline elements turning to box elements.
  <li>Another display type: <strong>inline-box</strong>. Image elements are set default in this type.
  <li><strong>display:none;</strong> Hide the element from the page and remove its space.
  <li><strong>visibility:hidden;</strong> Hide the element but keep its space. So there's an empty box/space for it.
  <li><strong>relative positioning: </strong> position:relative;
  <li>Relative positioning doesn't affect the position of anything else on screen.
  <li><strong>Absolute positioning: </strong> positioned relative to its parent element. For example, right:20px; means the element positioned 20px to the right boarder to its parent element.
  <li><strong>Fixed positioning: </strong> Keep the elements position when scrolling down.
  <li><strong>Attributes of positioning</strong> </li>
    <p>margin: 50px auto 0 auto; -- clockwise: top, right, bottom, left. </p>
    <p>margin: 0 auto; -- top&bottom left&right.</p>
  <li>
  </ul>
