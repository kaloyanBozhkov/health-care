<h1>Health & Care</h1>
<p>Have a go at the live version:<br/>www.kaloyanbozhkov.com/health&care/<br/>This is a good example of my current CSS3/JavaScript abilities, since it is one of the most recent projects of mine. I worked on it in my spare time throughout the last month, the total number of hours put into it is almost 28.</p>
<h2>What this prototype does</h2>
<p>Clicking anywhere on the below image will create a circle contianing the name of the body part that was clicked, as long as it is within a registered area. Otherwise, "Unassigned" is used when an unregistered area is clicked. Every circle which is within a registered area is saved to local storage, and pulled back when page is loaded. Double clicking a circle removes it from the DOM as well as from local storage, if it is saved.</p>
<h2>Existing & New Areas</h2>
<p>There are a few areas added by default, these are "Left Hand", "Right Hand", "Left Knee", "Right Knee", "Stomach", "Upper Back" and "Lower Back". In order to add new zones the "Enable New Area Addition" button must be clicked. After clicking siad button the next two clicks on the image will begin and end the selection of an area, instead of creating a circle. Once an area has been selected, a name can be assigned to it. For this prototype overlapping areas have not been considered, so it is advised to create new areas on parts of the image where no other ones already exist.</p>
<h2>Technologies used</h2>
<ul>
  <li>CSS3</li>
  <li>JavaScript</li>
  <li>Less</li>
  <li>JQuery</li>
  <li>HTML</li>
</ul>
<p>Everything showcased here is achieved by using CSS (with Less), HTML and JavaScript (with jQuery library), all of which is my own work. The positioning system, of both the circles and the selection area, is achieved through simple CSS. In particular, thanks to the height: auto style property, which allows the image to preserve its aspect ratio regardless of screen size, and the way absolute positioning with percentage values works. The strong advantage of such an implementation is that the browser is used to calculate these positions, instead of having to do the math only through JavaScript which would also require additional computation. Though, JavaScript is used to calculate the size of each circle when the window resizes, so that their sizes are in proportion to the new image size.</p>
