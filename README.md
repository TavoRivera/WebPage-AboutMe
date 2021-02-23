# Project 0 - Homepage by Octavio Rivera

    Web Programming with Python and JavaScript  

- [Project 0 - Homepage by Octavio Rivera](#project-0---homepage-by-octavio-rivera)
    - [Technologies](#technologies)
    - [Description](#description)

### Technologies

    -HTML5
    -SCSS
    -CSS
    -GIT

### Description

    This project consists in a personal resume that
    can be used as a way to know myself in a job
    opportunity for a recruiter. On my homepage I show you
    extra information about me and the world around me I also 
    added some photo galleries in case want to know me more.

    Within this repository you can find the directory
    called project0, inside it if you give "ls"
    you will find four .html files, a folder called assets, 
    a folder called icon for the icon of the webpage,
    in addition to the .md file, where I will explain to you
    about the content of each of these files.

    In index.html you will find my homepage, which is
    composed of a navbar, a header, some sections and 
    a footer. On this first page you will find the main 
    requirements of the project0, how to add a list, 
    a table and an image. I also made use of class and
    id to later style it in main.css using sass.

    Only the index.html uses main.css as a stylesheet,
    which is compiled by the sass compiler.

    starting with navbar, it is a bootstrap4 component that
    I have given a touch of personality with a file called
    _navbar.sass inside assets / scss / components / navbar
    where you can see the use of scss variables and selectors.

    Speaking of selectors throughout the project I made use of
    the following: Multiple Element Selector,
    Descendant selector, Child Selector, Pseudo Class Selector,
    Pseudo Element Selector. In addition to the use of class and
    id selector that you can see in the main.css and no_main.css
    files present at assets/css.

    After the navigation bar we continue with the
    header, this part has the style of views /
    homepage / __ homepage.scss and components /
    header / _header.scss in assets.

    In the case of _header it is responsible for using
    keyframes to make a small animation, also using
    media query. In _homepage I put the starting
    background image and I put a color on top of it to
    make the letters more visible.

    In the sections part, to style the table, list and
    paragraphs I used components / sections / _sections.
    scss where you can see the use of inheritance, nesting
    and more media queries to make the site more responsive.

    At the bottom is the footer, styled by components /
    footer / _footer.scss where I make use of many css
    properties to place the social media icons and give
    those cool animations.

    The use of the bootstrap classes and their columns
    were very important for the ordering of the content on
    this site, classes that were called within the index.html.

    In the case of logros.html, pets.html and
    galeria.html are styled by no_main.css within the
    assets / css directory.

    no_main.css adopts properties from main.css only to
    style the navbar and footer so they always look the
    same. The rest was done directly in the no_main.css
    document to give size styles, animations to the
    galleries within the html sheets mentioned above,
    without the need to use a framework.

    To finish in these html sheets apart from index they
    following the same styles of no_main.css, so I will only
    explain how I do it in logros.html.

    Inside section there is an ul with the class "gallery"
    that gives order, sizes and spaces to all the images
    that we insert in it, where each image contains an id
    so that once we click on that image it enters the
    class "modo" which will take care of sizing that image
    relative to the size of the screen, to be wider and
    that each image can be seen a title and can be changed
    to the next or previous image using the id.

    This was the first time that I made a web page from
    scratch, it was very difficult to start but I thank
    God and those who helped me with my queries and their
    advice to present something beautiful and adaptive.









