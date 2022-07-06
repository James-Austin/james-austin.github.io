<!--!DOCTYPE html is not included in this template as it is added by Pandoc. If Pandoc is not used to convert then DOCTYPE may need to be added manually>
<html>
<head>
<meta charset="utf-8">
<title>Audio  - Cool Code 2</title>
<!--CSS stylings-->
<style>
.title{}<!--this class name isspecific to Pandoc which introduces a duplicate title to the HTML document if the 'display:none;' attribute is not included-->
display:none;}
<!-- Other CSS styles can be included here if needed-->
</style>
</head>
body>
<a href="#mainContent">Skip to main content</a>
<header> <!-- banner landmark-->
<!-- img src="" alt=""> Creates placeholder for logo and provides text ddescription-->
</header>
<nav>
<!--aria-label="" if desired will allow me to rename the navigation region-->
</nav>

<main id="mainContent">

<h1>Audio</h1>

<audio controls> <!--'Controls' introduces media controls for the audio player-->
src="./source media/Edward VIII abdication speech.mp3" <!--path to audio file-->
</audio>

<div role="region" aria-label="Transcript"> <!--Changing the role to 'region' allows me to create new landmarks at will when combined with the aria-label-->
<details>

<summary role="button"><h3><!--Summary title</h3></summary>
<!--When combined with the CSSstyling for the details/summary component, (please see above), the rendered component works as both an expandable heading and button. However, the level may need to change depending on the other levels within the page.-->

Example transcript text.

</details>
</main>
<footer>
</footer>
</body>
</html>