TileyTiles
==========
UPDATE: New and improved Tiles 2.0! New animations, same great cross-browser SharePoint compatibility, with less code!
Check out http://kaceycoughlin.com/tiles/tiles2.html for a demo! 

UI tiles similar to Metro style tiles, using ONLY CSS3, no Javascript! This way, it can easily be used in a Script Editor Webpart for SharePoint!
If using in Script Editor Webpart: Just copy the code in the demo.html file (only stuff between style and body tags, leave everything else out.

Usage
======

File out links on each tile within the "label":

    <div class="mini-container">
    		<div class="tile2 tiles adjust" onclick="">
    		    <img src="img/question.png">
    		    <div class="label">
    		        <a href="">FAQ</a>
    		    </div>
    		</div>
		
Each tile div has optional "onclick" event for better UX.
Each "label" can contain a ul with added links, notes:

    <div class="mini-container">
    		<div class="tile2 tiles adjust" onclick="">
    		    <img src="img/question.png">
    		    <div class="label">
    		        <a href="">FAQ</a>
                            <ul>
                                <li>Have a question or problem?</li>
                           </ul>
    		    </div>
    		</div>
    		
There are 3 tile sizes:

<ul>
<li>125x125 square</li>
<li>125x250 rectangle</li>
<li>250x250 square</li>
</ul>

There are 2 containers for different float combinations:
<ul>
<li>mini-container: floats left</li>
<li>micro-container: no float (used inside mini-container)</li>
</ul>

License
=======
Feel free to use! Weeeeeeee!

Licensed under the MIT license
