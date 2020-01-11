# Anthony Tabura's csPortfolio

<details>
 <summary>Webpage</summary>
 <h3>Links:</h3>
 <p>
  
  <a href="https://taburaa.github.io/YummuInMyTummu/1test/tummu.html">Yummu in my Tummu<br></a>
  
  <a href="https://github.com/TaburaA/YummuInMyTummu">Web page URL<br></a>
    <details>
    <summary>Webpage Reflection</summary>
 <p>
I thought the webpage project was really cool. I've never used HTML before so to be able to use it and play around made it really cool. This lab had us use kate and HTML to create a webpage for something we liked. I used it to advertise Cornflakes and my friend Ben's band. I was able to make the images distort and redirect to other webpages. Really cool project.
</p>
    </details>
</p>
</details>

 <details>
 <summary>Dice Lab!</summary>
 <h3>Links:</h3>
  <p>
  
  <a href="https://taburaa.github.io/dice3/">DiceDiceBaby<br></a>
  
  <a href="https://github.com/TaburaA/dice3">Repo URL<br></a>
 <details>
    <summary>Dice Reflection</summary>
 <p>
This lab reviewed both math.Random() and object creation. My lab created dice objects where when you click on the screen, the color of the dice was randomized, along with the number displayed on the dice. The number on the dice was added to all the other dice, and the sum was calculated. If the sum was above a certain number, a "Win" was displayed with a congratulations and a picture of Dr. R.
</p>
    </details>

</p>
 </details>
 <details>
 <summary>UT Austin College Presentation!</summary>
 <h3>Links:</h3>
   <p>
  
  <a href="https://taburaa.github.io/CollegePresentation/yo.html">UT Austin Presentation<br></a>
  <details>
    <summary>UT Austin Reflection</summary>
 <p>
This college presentation project was very eye-opening. I was able to actually talk to people who work in computer science and see what it's like in a top 10 college. Many times we get so caught up in the everyday, that we forget what CS can actually look like. Computer science can be used to do a lot of cool things, and I was able to talk to UT Austin proffesors who can make cool things happen. I learnt a lot about UT Austin, and in the presentation I talked about the demographics, statistics and interesting projects that the CS department is doing there.
</p>
    </details>
</p>
 </details>
 <details>
 <summary>ChemoTaxis Lab!(JS)</summary>
 <h3>Links:</h3>
   <p>
    
<a href="https://taburaa.github.io/chemotaxis4/">Non-JS ChemoTravis(may not be working 100%!)<br></a>  
  
  <a href="https://taburaa.github.io/chemotaxis4/AJsound/">ChemoTravis<br></a>
  
  <a href="https://github.com/TaburaA/chemotaxis4">Repo URL<br></a>
 <details>
    <summary>ChemoTaxis Reflection</summary>
 <p>
This is my favorite lab so far. I've always been a rap fan. I thought that ChemoTaxis sounded a lot like ChemoTravis, which is the first name of one of my favorite rappers: Travis Scott. So I decided to implement my love for rap music into this lab. This lab tested math.random() pathing and object creation. Using PImage, math.random(), and sin()/theta/tan(), I created a program that featured 8-but pictures that moved towards where the mouse was. With a little help from Dr. R, I was able to get sound to work for the program in JS. If you pressed 1,2, or 3, the Travis Scott heads would shake at differing rates, and a soundbyte of one of his songs would play. A lot of different ideas in one lab.
</p>
    </details>

</p>
 </details>
 <details>
 <summary>Starfield Lab!</summary>
 <h3>Links:</h3>
    <p>
  
  <a href="https://taburaa.github.io/starfield5/">Thanksgiving Starfield<br></a>
  
  <a href="https://github.com/TaburaA/starfield5">Repo URL<br></a>
 <details>
    <summary>Starfield Reflection</summary>
 <p>
For this lab we were to focus on inheritance and interfaces. My lab used triginometry, PImage and randomization to create the image of turkeys flying in random increments in a circle, along with a giant corn and pilgrim hats. Since Thanksgiving was around the corner, this lab was Thanksgiving themed. The turkeys had their own code, and by using inheritence and interfaces, the other two images were able to follow the same code without any additional work. I learnt a lot about inheritence and interfaces, much more than last year.
</p>
    </details>

</p>
 </details>

<details>
 <summary>More Reflections</summary>
 <p>
  
 1. Individual Lab Reflections are under their respective dropdown menus.
 
 </p>
 <p>
	
  2. The thing I'm most proud of in my CS development is my ability to make my code my own. Throughout the labs and projects, we had checklists to fill, and deadlines to meet, yet I always went above and beyond to implement things that made it unique to me. Whether it would be to use PImages, sound bytes, or increased interactiveibility, I always enriched my education by going further than the call of duty. 
  
  </p>
  
  <p>
	
 3. Here's an examle as a code snippet:
 
 </p>
 
   ```Java
  text("Get 350 or more to win!",20,450);
  
  
 text("Total:", 20,550);
 
 
  text(total,120,550); 
  
  
   if(total>350){
   
   
    textSize(32);
    
    
    fill(255);
    
    
    text("YOU WIN!",200,550);
    
    
    image(img,210,150);
    
    
   }
   
  total=0;
  
 ```
 <p>
	
 While this is an early example, I still made it my own. Instead of just having a You Win message, I learnt how to use Images in processing and put in an image of Dr. R. 
 
 </p>
 
 <p>
	
 4. The most difficult piece of code would be the use of javascript to combine images, sound, and keyPressed() to make an interactive project!
 
 </p>
 <p>
	
 5. Here's the code:</p>
```Java
 function preload() {
	one = loadSound("data/straightup.wav");
	two = loadSound("data/skrt.wav");
	three = loadSound("data/itslit.mp3");
	img = loadImage("data/scott.png");
}


if (key == '1') {
		sike = 1;
		adlib = 0;
		while (adlib < 1) {
			one.play();
			adlib = 1;
		}
 
  
  	move(sike) {
		//var oliver = atan((mouseY - y) / (mouseX - x));
		var oliver = Math.PI * 2;
		if (sike == 1) {
			this.x += random(-5, 5);
			this.y += random(-5, 5);
			if (mouseX < this.x) {
				this.x -= cos(oliver) * 1;
				this.y -= sin(oliver) * 1;
			} else {
				this.x += cos(oliver) * 1;
				this.y += sin(oliver) * 1;
			}
		}

```
<p>
	
6. This code was challenging because I wanted to use the sound library of processing, but I coudln't because it wasn't available on github. I also wanted the objects I created to go straight to the mouse, but it the object would always go in zig zag fashion. In order to fix this, the code was converted to java script. It used function preload() along with loadsound() and loadimage() to load the files into the program. Then, I found out how to use keyPressed() to emit images and sound in an efficient way. To make the objects move in a straight line, I used trigonometry to create a line that went along either the cos or the sin of the angle. This would create a straight line from the orgin to the mouse. 

 </p>
 </details>
<details>
 <summary>TransitTree Final Project(Not 100% Working-Look in "details"!)</summary>
 <h3>Links:</h3>
    <p>
  
  <a href="https://taburaa.github.io/TransitTree/">Transit Tree<br></a>
  
  <a href="https://github.com/TaburaA/TransitTree">Repo URL<br></a>
 <details>
    <summary>Transit Tree Details</summary>
 <p>
Using a tree, people answer binary questions to find out what transportation they should use to get to their destination. The GH webpage won't work because the RIGHT key won't function, but it's fully functioning in processing.
</p>
    </details>

</p>
 </details>
