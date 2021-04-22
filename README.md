# PSLIB JUMPUJE
**Author:** *Barbora Polednová a Julie Sanetrníková*
## Popis hry (aneb vo co tady de)
Demo site pro zobrazení "finálního" výplodu **[demo typography-css-library site](https://pslib-cz.github.io/2020l4web-typography-css-library-BarboraPolednova/)** for full preview.
## Dependecies
### CSS files & Scripts
```
 <link rel="stylesheet" href="typography_style_format.css">
```
 This is the main CSS file, which includes typography and styling for the **html** tags. It needs to be placed in the head of your project.

 ```
 <link rel="stylesheet" href="gallery_format.css">
 <script src="https://unpkg.com/smartphoto@1.1.0/js/smartphoto.min.js"></script>
 <link rel="stylesheet" href="https://unpkg.com/smartphoto@1.1.0/css/smartphoto.min.css" />
```
For **image formating** and **image gallery usage** this fragment has to be copied in head.

 ```
 <script>
    new SmartPhoto(".thumbnails figure a");
</script>
```
To make this whole thing work, this **scrpit** needs to be placed right **under the body** of your code.
## Implementation
#### Place the code as your head of your project:
```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Typography template</title>
    <link rel="stylesheet" href="./typography_style_format.css">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&display=swap"
        rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Fjalla+One&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./author.css">
    <script src="https://unpkg.com/smartphoto@1.1.0/js/smartphoto.min.js"></script>
    <link rel="stylesheet" href="https://unpkg.com/smartphoto@1.1.0/css/smartphoto.min.css" />
    <link rel="stylesheet" href="./gallery_format.css">
</head>
```

#### Place the following script right under the body of your project:
 ```
 <script>
    new SmartPhoto(".thumbnails figure a");
</script>
