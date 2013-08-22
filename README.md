/* TilelyTiles
 * Written by Kacey Coughlin
 * Creative Commons license
 */

TileyTiles
==========

UI tiles similar to Metro style tiles, using ONLY CSS3, no Javascript! This way, it can easily be used in a Script Editor Webpart for SharePoint!
If using in Script Editor Webpart: Just copy the code in the demo.html file (only stuff between <style> and <body>, leave everything else out.

Useage
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

-125x125 square
-125x250 rectangle
-250x250 square

There are 2 containers for different float combinations:

-mini-container: floats left
-micro-container: no float (used inside mini-container)

