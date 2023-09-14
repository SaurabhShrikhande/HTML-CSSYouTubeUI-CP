# HTML-CSSYouTubeUI-CP


HTML-
<!DOCTYPE html>: Declares the document type and version as HTML5.
<html lang="en">: Defines the HTML document with the English language.
<head>: Contains meta-information and external resources.
<meta charset="UTF-8">: Specifies character encoding as UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>YouTube Clone</title>: Sets the title of the webpage to "YouTube Clone."
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet" />: Links to external font icons.
<link rel="stylesheet" href="./styles.css">: Links to an external CSS file.
<body>: Represents the main content of the webpage.
<div class="header">: Defines the header section of the page.
<div class="header_left">: Contains elements on the left side of the header.
<i class="material-icons">menu</i>: Displays a menu icon using Material Icons.
<img src="..." alt="youtube_image">: Displays an image with an alternative text.
<div class="header_search">: Contains the search bar in the header.
<form action="">: Defines a form for input elements.
<input type="text" placeholder="Search">: Creates a text input field with a placeholder.
<button><i class="material-icons">search</i></button>: Adds a search button with an icon.
<div class="header_icons">: Contains icons in the header for various actions.
<div class="main">: Represents the main content section of the webpage.
<div class="sidebar">: Defines a sidebar section.
<div class="sidebar_categories">: Contains categories within the sidebar.
<div class="sidebar_category">: Represents a single sidebar category.
<i class="material-icons">...</i>: Displays icons using Material Icons.
<span>...</span>: Contains text content.
<hr>: Inserts a horizontal line (separator).
<div class="videos">: Represents the videos section.
<h1>Recommened</h1>: Displays a heading for recommended videos.
<div class="videos_container">: Contains the video elements.
<div class="video">: Represents a single video item.
<div class="video_thumbnail">: Contains the video thumbnail image.
<img src="..." alt="">: Displays the video thumbnail.
<div class="video_details">: Contains video details like title and author.
<div class="author">: Displays the author's image.
<div class="title">: Contains the video title, author name, and views.
<a href="">: Defines a link element (empty href in this case).
<span>...</span>: Contains additional text information about the video.


CSS-
*:

Targets all elements on the page.
Resets margin, padding, and sets the box-sizing property to border-box for all elements.
body:

Styles the entire document's body.
Sets the font-family to 'Roboto' or a sans-serif font if 'Roboto' is unavailable.
.material-icons:

Targets elements with the class 'material-icons'.
Sets the color to a shade of gray (RGB 96,96,96).
.header:

Targets elements with the class 'header'.
Defines the header section with flex display, space-between alignment, a fixed height, and padding.
.header_left:

Targets elements with the class 'header_left'.
Configures the left part of the header with flex display and centered alignment.
.header_left img:

Targets images within elements with the class 'header_left'.
Sets a specific width and margin to the left.
.header_left i:

Targets icons within elements with the class 'header_left'.
Adds padding and a pointer cursor.
.header_search form:

Targets forms within the header.
Adds border, height, and sets display to flex.
.header_search input:

Targets input fields within the header search form.
Specifies width, padding, and removes border and border-radius.
.header_search button:

Targets buttons within the header search form.
Removes padding, margin, border, and border-radius.
.main:

Styles the main content section.
Sets flex display, hides overflow, and calculates the height to take up the remaining viewport height after the header.
.sidebar:

Styles the sidebar section.
Sets a fixed width, background color, and allows vertical scrolling when content overflows.
.sidebar_categories:

Styles the container for sidebar categories.
Defines a flex layout with column direction and adds margin.
.sidebar_category:

Styles individual sidebar categories.
Aligns items horizontally with padding and hover effect.
.sidebar_category span:

Styles text within sidebar categories.
Adds left margin.
.sidebar_category:hover:

Styles sidebar categories on hover.
Changes the background color and cursor to a pointer.
.sidebar::-webkit-scrollbar:

Targets the scrollbar in the sidebar.
Hides the scrollbar in Webkit-based browsers.
hr:

Styles horizontal lines.
Sets a background color and removes border.
.videos:

Styles the videos section.
Adds background color, padding, and allows vertical scrolling when content overflows.
.videos_conatiner:

Styles the container for video elements.
Sets a flex layout, justifies content, and allows wrapping.
.video:

Styles individual video elements.
Specifies a fixed width and margin.
.video_thumbnail:

Styles video thumbnails.
Sets the width and height, and adjusts the image's size and aspect ratio.
.video_details:

Styles the video details section.
Configures a flex layout with a horizontal direction and margin.
.title:

Styles the title of a video.
Uses a flex layout with a column direction.
title h3:

Styles video titles.
Sets color, line-height, font size, and margin.
.title a,span:

Styles links and spans within video titles.
Sets text decoration, color, and font size.
h1:

Styles the level 1 heading element.
Sets font size, margin, and color.
