---
layout: post
title: Baroque On Bamboo, Cantata 209, J.S. Bach
categories: [music] 
image:
    feature: 
---
<html>
<head>
<meta charset="utf-8" />
<!-- Website Design By: www.happyworm.com -->

<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<link href="/dist/skin/blue.monday/css/jplayer.blue.monday.min.css" rel="stylesheet" type="text/css" />
<script type="text/javascript" src="/dist/lib/jquery.min.js"></script>
<script type="text/javascript" src="/dist/jplayer/jquery.jplayer.min.js"></script>
<script type="text/javascript" src="/dist/add-on/jplayer.playlist.min.js"></script>
<script type="text/javascript">
//<![CDATA[
$(document).ready(function(){

	var myPlaylist = new jPlayerPlaylist({
		jPlayer: "#jquery_jplayer_N",
		cssSelectorAncestor: "#jp_container_N"
	}, [
		 {
				title:"Bach Cantata 209",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/cantata209.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
	], {
		playlistOptions: {
			enableRemoveControls: true
		},
		swfPath: "/dist/jplayer",
		supplied: "webmv, ogv, m4v, oga, mp3",
		useStateClassSkin: true,
		autoBlur: false,
		smoothPlayBar: true,
		keyEnabled: true,
		audioFullScreen: true
	});

	// Click handlers for jPlayerPlaylist method demo

	// Audio mix playlist

	$("#playlist-setPlaylist-audio-mix").click(function() {
		myPlaylist.setPlaylist([
			{
			title:"Pavane - Faure",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/pavane.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
            {
			title:"Pictures At An Exhibition - Mussorgsky",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/pictures-at-an-exhibition.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{				
				title:"Adagio",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/adagio.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
					title:"Andalouse",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/andalouse.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
					title:"Meditation",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/meditation.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
				title:"Dvorak",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/dvorak.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
                title:"Whistles",
			artist:"El Misterio",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/whistles.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
                title:"John Dowland Songs",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/dowland.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
                title:"Nocturne - Chopin",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/nocturne.mp3",
			poster: "https: //elmisterio.org/images/nochedesierto.jpg"
			},
			{
                title:"Anandamurti Melodies",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/anandamurti.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
                title:"William Enckhausen plays Heinrich Enckhausen, Handel, and Telemann",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/enckhausen.mp3",
			poster: "https: //elmisterio.org/images/contemplations.jpg"
			},
			{
                title:"Reverie - Debussy",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/reverie.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
                title:"Dance Of The Blessed Spirits",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/blessed-spirits.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
                title:"Los Doraditos",
			artist:"quetzal",
			mp3:"http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/los-doraditos.mp3",
			poster: "http://quetzalwill.org/images/contemplations.jpg"                                                                                     
			}
		]);
	});

	// Video mix playlist

	$("#playlist-setPlaylist-video-mix").click(function() {
		myPlaylist.setPlaylist([
			{
			    title:"Govinda",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/govinda.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
			    title:"Topilejo",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/topilejo.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"Padmasambhava",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/padmasambhava.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"Baba Nam Kevalam",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/babanamkevalam.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"Soja",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/soja.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"Om Ah Hum Vajra Guru",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/om-ah-hum-vajra-guru.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"Nikte Ha Kiirtan",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/nikteha.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"Reverie Kiirtan",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/reverie-kiirtan.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"Desierto",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/desierto2.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"Tiny Green Island",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/tiny-green-island.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"La Gracia",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/gracia.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			},
			{
				title:"Los Doraditos",
				artist:"El Misterio",
				mp3:"http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/los-doraditos.mp3",
				poster: "http://quetzalwill.org/images/kiirtan.jpg"
			}
		]);
	});

	// Media mix playlist

	$("#playlist-setPlaylist-media-mix").click(function() {
		myPlaylist.setPlaylist([
            {
				title:"Bach Cantata 209",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/cantata209.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
            {
				title:"Tambourin - Rameau",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/tambourin.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
				title:"Gavotte And Minuet - Bach",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/gavotte-minuet.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
				title:"Gavotte - Handel",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/gavotte-handel.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
            {
				title:"Air and Gavotte - Bach",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/air-gavotte.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
				title:"Italian Air - Telemann",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/italian-air.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
				title:"Christmas Oratorio - Bach",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/christmas-oratorio.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
				title:"Sonata in B-minor - Bach",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/sonata-b-minor.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			},
			{
				title:"Minuet, Air, and Bouree - Bach",
				artist:"quetzal",
				mp3:"http://quetzalwill.org/assets/music/Baroque-On-Bamboo/minuet-air-bouree.mp3",
				poster: "http://quetzalwill.org/images/contemplations.jpg"
			}
		]);
	});

	


	// The remove commands

	$("#playlist-remove").click(function() {
		myPlaylist.remove();
	});

	$("#playlist-remove--2").click(function() {
		myPlaylist.remove(-2);
	});
	$("#playlist-remove--1").click(function() {
		myPlaylist.remove(-1);
	});
	$("#playlist-remove-0").click(function() {
		myPlaylist.remove(0);
	});
	$("#playlist-remove-1").click(function() {
		myPlaylist.remove(1);
	});
	$("#playlist-remove-2").click(function() {
		myPlaylist.remove(2);
	});

	// The shuffle commands

	$("#playlist-shuffle").click(function() {
		myPlaylist.shuffle();
	});

	$("#playlist-shuffle-false").click(function() {
		myPlaylist.shuffle(false);
	});
	$("#playlist-shuffle-true").click(function() {
		myPlaylist.shuffle(true);
	});

	// The select commands

	$("#playlist-select--2").click(function() {
		myPlaylist.select(-2);
	});
	$("#playlist-select--1").click(function() {
		myPlaylist.select(-1);
	});
	$("#playlist-select-0").click(function() {
		myPlaylist.select(0);
	});
	$("#playlist-select-1").click(function() {
		myPlaylist.select(1);
	});
	$("#playlist-select-2").click(function() {
		myPlaylist.select(2);
	});

	// The next/previous commands

	$("#playlist-next").click(function() {
		myPlaylist.next();
	});
	$("#playlist-previous").click(function() {
		myPlaylist.previous();
	});

	// The play commands

	$("#playlist-play").click(function() {
		myPlaylist.play();
	});

	$("#playlist-play--2").click(function() {
		myPlaylist.play(-2);
	});
	$("#playlist-play--1").click(function() {
		myPlaylist.play(-1);
	});
	$("#playlist-play-0").click(function() {
		myPlaylist.play(0);
	});
	$("#playlist-play-1").click(function() {
		myPlaylist.play(1);
	});
	$("#playlist-play-2").click(function() {
		myPlaylist.play(2);
	});

	// The pause command

	$("#playlist-pause").click(function() {
		myPlaylist.pause();
	});

	// Changing the playlist options

	// Option: autoPlay

	$("#playlist-option-autoPlay-true").click(function() {
		myPlaylist.option("autoPlay", true);
	});
	$("#playlist-option-autoPlay-false").click(function() {
		myPlaylist.option("autoPlay", false);
	});

	// Option: enableRemoveControls

	$("#playlist-option-enableRemoveControls-true").click(function() {
		myPlaylist.option("enableRemoveControls", true);
	});
	$("#playlist-option-enableRemoveControls-false").click(function() {
		myPlaylist.option("enableRemoveControls", false);
	});

	// Option: displayTime

	$("#playlist-option-displayTime-0").click(function() {
		myPlaylist.option("displayTime", 0);
	});
	$("#playlist-option-displayTime-fast").click(function() {
		myPlaylist.option("displayTime", "fast");
	});
	$("#playlist-option-displayTime-slow").click(function() {
		myPlaylist.option("displayTime", "slow");
	});
	$("#playlist-option-displayTime-2000").click(function() {
		myPlaylist.option("displayTime", 2000);
	});

	// Option: addTime

	$("#playlist-option-addTime-0").click(function() {
		myPlaylist.option("addTime", 0);
	});
	$("#playlist-option-addTime-fast").click(function() {
		myPlaylist.option("addTime", "fast");
	});
	$("#playlist-option-addTime-slow").click(function() {
		myPlaylist.option("addTime", "slow");
	});
	$("#playlist-option-addTime-2000").click(function() {
		myPlaylist.option("addTime", 2000);
	});

	// Option: removeTime

	$("#playlist-option-removeTime-0").click(function() {
		myPlaylist.option("removeTime", 0);
	});
	$("#playlist-option-removeTime-fast").click(function() {
		myPlaylist.option("removeTime", "fast");
	});
	$("#playlist-option-removeTime-slow").click(function() {
		myPlaylist.option("removeTime", "slow");
	});
	$("#playlist-option-removeTime-2000").click(function() {
		myPlaylist.option("removeTime", 2000);
	});

	// Option: shuffleTime

	$("#playlist-option-shuffleTime-0").click(function() {
		myPlaylist.option("shuffleTime", 0);
	});
	$("#playlist-option-shuffleTime-fast").click(function() {
		myPlaylist.option("shuffleTime", "fast");
	});
	$("#playlist-option-shuffleTime-slow").click(function() {
		myPlaylist.option("shuffleTime", "slow");
	});
	$("#playlist-option-shuffleTime-2000").click(function() {
		myPlaylist.option("shuffleTime", 2000);
	});

	// Equivalent commands

	$("#playlist-equivalent-1-a").click(function() {
		myPlaylist.add({
			title:"Your Face",
			artist:"The Stark Palace",
			mp3:"http://www.jplayer.org/audio/mp3/TSP-05-Your_face.mp3",
			oga:"http://www.jplayer.org/audio/ogg/TSP-05-Your_face.ogg",
			poster: "http://www.jplayer.org/audio/poster/The_Stark_Palace_640x360.png"
		}, true);
	});

	$("#playlist-equivalent-1-b").click(function() {
		myPlaylist.add({
			title:"Your Face",
			artist:"The Stark Palace",
			mp3:"http://www.jplayer.org/audio/mp3/TSP-05-Your_face.mp3",
			oga:"http://www.jplayer.org/audio/ogg/TSP-05-Your_face.ogg",
			poster: "http://www.jplayer.org/audio/poster/The_Stark_Palace_640x360.png"
		});
		myPlaylist.play(-1);
	});

	// AVOID COMMANDS

	$("#playlist-avoid-1").click(function() {
		myPlaylist.remove(2); // Removes the 3rd item
		myPlaylist.remove(3); // Ignored unless removeTime=0: Where it removes the 4th item, which was originally the 5th item.
	});


});
//]]>
</script>
</head>
<body>
<p style="margin-top:1em;">


<div id="jp_container_N" class="jp-video jp-video-270p" role="application" aria-label="media player">
	<div class="jp-type-playlist">
		<div id="jquery_jplayer_N" class="jp-jplayer"></div>
		<div class="jp-gui">
			<div class="jp-video-play">
				<button class="jp-video-play-icon" role="button" tabindex="0">play</button>
			</div>
			<div class="jp-interface">
				<div class="jp-progress">
					<div class="jp-seek-bar">
						<div class="jp-play-bar"></div>
					</div>
				</div>
				<div class="jp-current-time" role="timer" aria-label="time">&nbsp;</div>
				<div class="jp-duration" role="timer" aria-label="duration">&nbsp;</div>
				<div class="jp-controls-holder">
					<div class="jp-controls">
						<button class="jp-previous" role="button" tabindex="0">previous</button>
						<button class="jp-play" role="button" tabindex="0">play</button>
						<button class="jp-next" role="button" tabindex="0">next</button>
						<button class="jp-stop" role="button" tabindex="0">stop</button>
					</div>
					<div class="jp-volume-controls">
						<button class="jp-mute" role="button" tabindex="0">mute</button>
						<button class="jp-volume-max" role="button" tabindex="0">max volume</button>
						<div class="jp-volume-bar">
							<div class="jp-volume-bar-value"></div>
						</div>
					</div>
					<div class="jp-toggles">
						<button class="jp-repeat" role="button" tabindex="0">repeat</button>
						<button class="jp-shuffle" role="button" tabindex="0">shuffle</button>
						<button class="jp-full-screen" role="button" tabindex="0">full screen</button>
					</div>
				</div>
				<div class="jp-details">
					<div class="jp-title" aria-label="title">&nbsp;</div>
				</div>
			</div>
		</div>
		<div class="jp-playlist">
			<ul>
				<!-- The method Playlist.displayPlaylist() uses this unordered list -->
				<li>&nbsp;</li>
			</ul>
		</div>
		<div class="jp-no-solution">
			<span>Update Required</span>
			To play the media you will need to either update your browser to a recent version or update your <a href="https://get.adobe.com/flashplayer/" target="_blank">Flash plugin</a>.
		</div>
	</div>
</div>
			
&nbsp;


&nbsp;

<code><strong>To Continue Listening To Other Tracks Choose A Playlist:</strong>
<li> </li>
<li> <a href="javascript:;" id="playlist-setPlaylist-audio-mix"><strong>Contemplations On A Quena </strong></a>- classical solos</li> 
<li> <a href="javascript:;" id="playlist-setPlaylist-video-mix"><strong>Meditation Chants </strong></a>- meditation chants with our community, "El Misterio"</li> 
<li> <a href="javascript:;" id="playlist-setPlaylist-media-mix"><strong>Baroque On Bamboo </strong></a>- Baroque solos</li> </code><br />
&nbsp;
<li></li>
<strong><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena.zip" download="Contemplations-on-a-Quena.zip">Download Contemplations On A Quena. </a></strong>
<li></li>
<strong><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio.zip" download="Kiirtan-el-Misterio.zip">Download Meditation Chants </a></strong>
<li></li>
<strong><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo.zip" download="Baroque-On-Bamboo.zip">Download Baroque On Bamboo </a><strong>
<li></li>
<li><strong>DOWNLOAD INDIVIDUAL TRACKS </strong>  (If download link opens to play instead of downloading, then right-click on the player to download the individual track.)</li>
<li></li>
"Contemplations On A Quena"

<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/pavane.mp3"> Pavane.mp3</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/pictures-at-an-exhibition.mp3"> Pictures At An Exhibition.mp3</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/adagio.mp3"> Adagio de Marcello</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/andalouse.mp3"> Andalouse de Pessard</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/meditation.mp3"> Meditation de Massenet</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/dvorak.mp3"> Dvorak Medley</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/whistles.mp3"> Amazon Whistle</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/dowland.mp3"> John Dowland Songs</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/nocturne.mp3"> Nocturne de Chopin</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/anandamurti.mp3"> Anandamurti Melody</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/enckhausen.mp3">William Enckhausen plays Heinrich Enckhausen</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/reverie.mp3"> Reverie de Debussy</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/blessed-spirits.mp3"> Dance of the Blessed Spirits</a></li>
<li><a href="http://quetzalwill.org/assets/music/Contemplations-On-A-Quena/los-doraditos.mp3"> Los Doraditos</a></li>
<li></li>
"Meditation Chants"
 
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/esperanza.mp3" > "Song of Hope"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/govinda.mp3" > "Govinda"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/topilejo.mp3" > "Topilejo"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/padmasambhava.mp3" > "Padmasambhava"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/babanamkevalam.mp3" > "Baba Nam Kevalam"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/soja.mp3" > "Tribute"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/om-ah-hum-vajra-guru.mp3" > "Om Ah Hum Vajra Guru Padme Siddhi Hum"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/nikteha.mp3" > "Nikte Ha Kiirtan"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/reverie-kiirtan.mp3" > "Reverie Kiirtan"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/desierto2.mp3" > "El Desierto Kiirtan"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/tiny-green-island.mp3" > "Tiny Green Island"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/gracia.mp3" > "La Gracia"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Kiirtan-El-Misterio/los-doraditos.mp3" > "Los Doraditos"</a></li>
<li></li>
"Baroque On Bamboo"
 
<li><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo/cantata209.mp3"> Cantata 209 - Bach</a></li>
<li><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo/tambourin.mp3"> Tambourin - Rameau</a></li>
<li><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo/gavotte-minuet.mp3" > "Gavotte & Minuet - Bach"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo/gavotte-handel.mp3"> Gavotte - Handel</a></li>
<li><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo/air-gavotte.mp3" > "Air & Gavotte - Bach"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo/italian-air.mp3"> Italian Air - Telemann</a></li>
<li><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo/christmas-oratorio.mp3" > "Christmas Oratorio - Bach"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo/sonata-b-minor.mp3" > "Sonata in B-minor - Bach"</a></li>
<li><a href="http://quetzalwill.org/assets/music/Baroque-On-Bamboo/minuet-air-bouree.mp3" > "Minuet, Air, & Bouree in E-minor - Bach"</a></li>




