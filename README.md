# distantjob

Transparent Background (.8) in .hero was upper .hero__title. Text .hero__title was also with this transparent background. But .btns in .hero -- display normal without transparent background. 
	So, must be 
		.hero__title {position: relative;}
		
In webpack must change: 
		1. Set "destpath="
		2. Index.yaml => inside just page.html

&:hover => &:hover,&:active	