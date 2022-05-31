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

  </ul>
