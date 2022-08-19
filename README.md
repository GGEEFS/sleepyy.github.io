
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta content="IE=edge" http-equiv="X-UA-Compatible">
	<link href="https://northernsi.de/ebiofavicon.ico" rel="icon" type="image/x-icon" />
	<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css" rel="stylesheet" />
	<meta content="width=device-width, initial-scale=1.0" name="viewport">
	<meta content="ebio.gg @ sleepyy" property="og:title" />
	<meta content="website" property="og:type" />
	<meta content="https://ebio.gg/sleepyy" property="og:url" />
	<meta content="{avatar_url}" property="og:image" />
	<meta content="Check out sleepyy's social links and profile!" property="og:description" />
	<meta content="#2C2F33" name="theme-color">
	<title>@sleepyy - ebio.gg</title>
</head>
<style>
	@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap');

	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		font-family: 'Poppins', sans-serif;
	}

	html,
	body {
		display: grid;
		height: 100%;
		width: 100%;
		place-items: center;
		background: linear-gradient(315deg, #000000 0%, #161616 74%);
	}

	.title {
		text-align: center;
	}

	.title .quote {
		margin-top: 5px;
	}

	.avatar {
		border: 5px solid #23272A;
		height: 200px;
		width: 200px;
		object-fit: cover;
		border-radius: 50%;
		position: relative;
		left: 10px;
	}

	.status {
		background-color: #23272A;
		padding: 5px;
		border-radius: 38px;
		z-index: 1;
		position: relative;
		top: -10px;
		left: -50px;
	}

	.wrapper .button {
		display: inline-block;
		height: 60px;
		width: 60px;
		float: left;
		margin: 0 5px;
		overflow: hidden;
		background: #fff;
		border-radius: 51px;
		cursor: pointer;
		box-shadow: 0px 10px 10px rgba(255, 145, 0, 0.1);
		transition: all 0.3s ease-out;
		color: black;
	}

	.wrapper .button:hover {
		width: 200px;
		color: black;
	}

	.wrapper .button .icon {
		display: inline-block;
		height: 60px;
		width: 60px;
		text-align: center;
		border-radius: 500px;
		box-sizing: border-box;
		line-height: 60px;
		transition: all 0.3s ease-out;
	}

	.wrapper .button .icon i {
		font-size: 25px;
		line-height: 60px;
		transition: all 0.3s ease-out;
	}

	.wrapper .button:hover .icon i {
		color: #fff;
	}

	.wrapper .button span {
		font-size: 20px;
		font-weight: 500;
		line-height: 60px;
		margin-left: 10px;
		transition: all 0.3s ease-out;
		color: black;
	}

	.footer p,
	h4,
	a {
		text-align: center;
		color: white;
	}


	/*
	--------------------------------------------
	*/

	.wrapper .button.discord:hover .icon {
		background: #5865F2;
	}

	.wrapper .button.discord span {
		color: #5865F2;
	}

	.wrapper .button.github:hover .icon {
		background: #333;
	}

	.wrapper .button.github span {
		color: #333;
	}

	.wrapper .button.tiktok:hover .icon {
		background: #000000;
	}

	.wrapper .button.tiktok span {
		color: #000000;
	}

	.wrapper .button.youtube:hover .icon {
		background: #c4302b;
	}

	.wrapper .button.youtube span {
		color: #c4302b;
	}

	.wrapper .button.twitch:hover .icon {
		background: #6441a5;
	}

	.wrapper .button.twitch span {
		color: #6441a5;
	}

	.wrapper .button.twitter:hover .icon {
		background: #00acee;
	}

	.wrapper .button.twitter span {
		color: #00acee;
	}

	.wrapper .button.snapchat:hover .icon {
		background: #FFFC00;
	}

	.wrapper .button.snapchat span {
		color: #FFFC00;
	}

	.wrapper .button.steam:hover .icon {
		background: #1b2838;
	}

	.wrapper .button.steam span {
		color: #1b2838;
	}

	.wrapper .button.instagram:hover .icon {
		background: #C13584;
	}

	.wrapper .button.instagram span {
		color: #C13584;
	}

	.wrapper .button.facebook:hover .icon {
		background: #4267B2;
	}

	.wrapper .button.facebook span {
		color: #4267B2;
	}

	.wrapper .button.spotify:hover .icon {
		background: #1DB954;
	}

	.wrapper .button.spotify span {
		color: #1DB954;
	}

	.wrapper .button.reddit:hover .icon {
		background: #FF5700;
	}

	.wrapper .button.reddit span {
		color: #FF5700;
	}

	.wrapper .button.soundcloud:hover .icon {
		background: #ff5500;
	}

	.wrapper .button.soundcloud span {
		color: #ff5500;
	}

	.wrapper .button.pinterest:hover .icon {
		background: #cc0000;
	}

	.wrapper .button.pinterest span {
		color: #cc0000;
	}

	.wrapper .button:hover .icon {
		background: #4078c0;
	}

	.wrapper .button span {
		color: #4078c0;
	}

	.badge {
		position: relative;
		display: inline-block;
		height: 28px;
		width: 28px;
	}

	.badge .badge-tooltiptext {
		visibility: hidden;
		width: 120px;
		background-color: #555;
		color: #fff;
		text-align: center;
		border-radius: 6px;
		padding: 5px 0;
		position: absolute;
		z-index: 1;
		bottom: 125%;
		left: 50%;
		margin-left: -60px;
		opacity: 0;
		transition: opacity 0.3s;
	}

	.badge .badge-tooltiptext::after {
		content: "";
		position: absolute;
		top: 100%;
		left: 50%;
		margin-left: -5px;
		border-width: 5px;
		border-style: solid;
		border-color: #555 transparent transparent transparent;
	}

	.badge:hover .badge-tooltiptext {
		visibility: visible;
		opacity: 1;
	}

	.editBtn {
		background-color: #282828;
		background-size: cover;
		border-radius: 7px;
		padding: 8px;
		color: white;
		cursor: pointer;
	}
</style>
<body style="background-image: url('https://64.media.tumblr.com/2843854df0b77a1bbc2aa5ef3583de6d/tumblr_nbetdtAkH31rbkx51o1_400.gifv'); background-size: cover;">
								
<div class="title">
	<div class="title-img">
		<img alt="Avatar" class="avatar" src="https://cdn.discordapp.com/avatars/990005422909960262/a_decc315cf4e4ecf7a0d171c69d6b6c54.gif?size=1024" onerror="this.src='https://cdn.discordapp.com/attachments/962052961905836142/993200463644196944/c09a43a372ba81e3018c3151d4ed4773.png'">
		<img alt="Status" class="status" src="https://cdn.discordapp.com/emojis/991069580589953105.webp" style="width: 32px; 32px" />
	</div>
	<h1 class="owner" style="color: #fedcdc">sleepyy</h1>
								
	<p class="quote" style="color: #f00000">
		im getting tired of life
	</p>
	
										<script>
											function getCookie(name) {
												const value = `; ${document.cookie}`;
												const parts = value.split(`; ${name}=`);
												if (parts.length === 2) return parts.pop().split(';').shift();
											}

											function followUser() {
												let xhr = new XMLHttpRequest();
												xhr.open('GET', `https://ebio.gg/api/followUser/990005422909960262?token=${getCookie('token')}&uID=${getCookie('uID')}`);
												xhr.send();
												location.reload();
											}
										</script>
										<button 
										        style="border-width: 0; background-color: rgba(255,255,255,0.89); border-radius: 8px; padding: 4px; font-size: 13px; width: max-content; margin: 5px auto 20px;">
											
											
										</button>
									
	 
</div>
<div class="wrapper">
	
						
</div>
<div class="footer">
	<h4><a href=""><b>sleepyy#0003</b></a></h4>
</div>
</body>
</html>
