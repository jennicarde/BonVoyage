/* iPads (Tablets) ----------- */
@media only screen and (min-width: 768px) and (max-width : 1024px){
/* Styles */

.desktop_only {
	display: none;
}

.container {
	background: #fff;
}

nav ul {
	/*display: block will force the ul to strech across full width of parent element (nav)*/
	display: block;
	}

nav ul li {
	padding: 10px 0;
	/* using % will allow to calculate a equal for each list item relative to the parent element (ul)*/
	width: 24%;
}
	nav ul li:last-child {
		border-right: none;
	}


section#main, aside {
	border-left: none;
	width: auto;
	padding: 10px 40px;
	margin: 10px 20px;
}

aside {
	background: #95a5a6;
}

footer {
	position: relative;
}


}

/*for small devices (landscape & portrait) */
@media only screen and (min-width : 320px) and (max-width: 767px) {
/* Styles */

header h1 {
	text-align: center;
}

nav {
	width: 100%;
	background: #95a5a6;
}

	nav ul {
		margin: 0;
		padding: 0;	
		clear:both;
		/*display: block will force the ul to strech across full width of parent element (nav)*/
		display: block;
		}

	nav ul li {
		padding: 10px 1.5%;
		width: 100%;
		border-bottom: 1px solid #fff;
		font-size: 20px;
		display: block;
	}


section#main, aside {
	float: none;
	border-left: none;
	width: auto;
	padding: 10px 40px;
	margin: 10px 20px;
}

footer {
	position: relative;
}


}