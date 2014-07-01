# Responsive Snow Theme #

The following css file works with Snow theme and designed to be responsive on Iphone 4,5 and Nexus 5 phones in the potrait mode.
I will be making further changes and pushing them to the repo.

How to use it.<br>
* 1) Download the file.
* 2) Goto folder qa-themes/Snow
* 3) Take a backup of your current theme file qa-styles.css
* 4) place this qa-styles.css in this folder
* 5) Voila you are done :) 
* 6) Core Changes/Hacks to correct the side-panel
	* a) Open qa-include/qa-theme-base.php
	* b) in the file find function body_content()
	* c) Change the order from 
			`	$this->sidepanel();
               $this->main();`
                
		to 
	     	`   $this->main();
				$this->sidepanel();`


