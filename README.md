# animatin30.08.22.rar
my work
body{
	margin: 0 auto;
	padding: 0;
}

.demo{
	width: 300px;
	height: 300px;
	background: red;
	float: left;
	display: flex;
	align-items: center;
	justify-content: center;
	position: relative;
	/*left: 250px;
	top: 250px;*/
	animation-duration: 4s;
	animation-name: demo;
}

@keyframes demo{
	from{
		transform: scale(0%);}
	to{
		transform: scale(100%);
	}
	0%{
		transform:scale
		
		background-size: cover;
		top: 0;
		left: 0;


	}
	25%{
		background-image: url(../img/panda-jpg.webp);
		background-size: cover;
		top: 0;
		left: 500px;


	}
	50%{
		background-image: url(../img/panda-jpg.webp);
		background: green;
		background-size: cover;
		top: 500px;
		left: 500px
	}
	75%{
		background-image: url(../img/panda.jpg);
		background: purple;
		background-size:cover;
		top: 500px;
		left: 0px; 

	}
	100%{
		background-image: url(../img/panda.jpg);
		background: blue;
		background-size: cover;
		top: 0;
		left: 0;
	}
}
