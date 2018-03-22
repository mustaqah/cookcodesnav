<<<<<<< HEAD
# cookcodesNav v1.0
## Responsive Mobile Menu jQuery Plugin
* * *
### Usage

#### Include the CSS & JS
cookcodesnav.css can be modified to fit website design

    <link rel="stylesheet" href="cookcodesNav/dist/cookcodesnav.min.css" />
    <script src="cookcodesNav/dist/jquery.cookcodesnav.min.js"></script>

#### Menu Markup

    <ul id="menu">
        <li><a href="#">item 1</a></li>
        <li><a href="#">item 2</a></li>
        <li><a href="#">item 3</a></li>
        <li><a href="#">item 4</a></li>
    </ul>
#### Initialize

    <script>
        $(function(){
            $('#menu').cookcodesnav();
        });
    </script>

### Options
 			label: 'MENU',
            duplicate: true,
            duration: 200,
            easingOpen: 'swing',
            easingClose: 'swing',
            closedSymbol: "&#10133;",
            openedSymbol: "&#10134;",
            prependTo: 'body',
            appendTo: '',
            parentTag: 'a',
            closeOnClick: true,
            allowParentLinks: true,
            nestedParentLinks: true,
            showChildren: false,
            removeIds: true,
            removeClasses: false,
            removeStyles: false,
			brand: 'LOGO',

=======
# cookcodesnav
Responsive Mobile Menu jQuery Plugin
>>>>>>> 012a6f9f60f9a679527ee0c61f8b0c787bafc3dc
