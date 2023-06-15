
   # There are 6 headings types (h1-h6)

<h1> This is an h1 heading</h1>
<h2>This is an h2 heading</h2>
<h3>This is an h3 heading</h3>
<h4>This is an h4 heading</h4>
<h5>This is an h5 heading</h5>
<h6>This is an h6 heading</h6>


# There are 3 ways to insert css code 

   ## 1. inline CSS -->
   
   **you give the opening tag a style attribute with the desired property: value pair**
 
<h1 style="color: blue">This is an h1 heading</h1>

    <p>
       This is a paragraph.
    </p>

**You can use lorem to create dummy text**

__p>lorem__

    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit ipsa ab, doloribus, quo mollitia porro repellat praesentium sapiente corrupti harum unde perspiciatis, voluptatem atque. Excepturi ab suscipit repudiandae a ipsum.
    Fuga est, nihil explicabo aliquid odio, nobis molestiae optio eum nesciunt illo nisi, repudiandae at ab aut sit nulla suscipit! Inventore, optio tempora accusantium porro ipsam reprehenderit! Consectetur, voluptas inventore?</p>

# Ordered and Unordered Lists

## Ordered lists

__ol>li*4__

<ol>
  <li>get up</li>
  <li>wash</li>
  <li>shave</li>
  <li>make coffee</li>
</ol>

## Unordered lists

__ul>li*4__

<ul>
  <li>mineral water</li>
  <li>coffee</li>
  <li>wine</li>
  <li>cigars</li>
</ul>

## Nested Lists

__ul>li>p+ul>li*2__

<ul>
    <li>
        <p>Item 1</p>
        <ul>
            <li>Subitem 1</li>
            <li>Subitem 2</li
        </ul>
    </li>
</ul>


# Classes and ID

## Classes

 **Classes are used to select more than one element**

__p.blue__

   <p class="blue">This is blue</p>
   <p class="red">This is red</p>
   <p class="blue">This is blue</p>
   <p class="red">This is red</p>

## IDs

**An ID selects a single item**

__p#red__   

<p id="green" class="red" style="color: yellow">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde iure expedita sapiente a enim nobis iusto beatae modi numquam cupiditate eligendi harum hic quia voluptates corporis, impedit voluptas exercitationem fugit.</p>

**id attributes are more specific than class attributes, and so in case of conflict, the id attribute prevails over class attributes.  Inline styles trump both ID and class attributes, unless the class or id comes with an "!important" declaration.**









