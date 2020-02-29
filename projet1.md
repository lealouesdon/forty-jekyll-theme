---
layout: post
title: WordGame Projet
description:
image: assets/images/jeudemots.png
nav-menu: false
show_tile: false
---

<h3>The Context</h3>
<p>This was a school project in a group of 4, organized using Scrum. We used Travis CI and SonarCould to ensure the quality of our code.</p>
<h3>The Goal</h3>
<p>The goal of this project was to create an online multiplayer word game.</p>

<h3>The Technologies</h3>
<p>We used Angular, node.js, hosted on Firebase. <br>
The challenge of this project was dealing the different async calls made by the players, as well as analyzing all the data in order to render statistics. 
<br> To manage async calls we used socket.io<p>

<img src="/forty-jekyll-theme/assets/images/jeudemots1.png" alt="" data-position="top center" />
<p>The player first chooses a username.</p>
<img src="/forty-jekyll-theme/assets/images/jeudemots2.png" alt="" data-position="top center" />
<p>A Username selected, the player arrives to the lobby. The first player is the admin of the game. In the lobby, they cans select the level of the game and the name of the team. Once all the players are in the lobby, the admin can start the game.</p>
<img src="/forty-jekyll-theme/assets/images/jeudemots3.png" alt="" data-position="top center" />
<p>The goal of the game is to find the word selected by the server. In order to do that, the players type in words. Each word has a score, and a number of correct letters, well positioned or not. The game ends when one of the players find the correct word. The length of the word selected is based on the level selected by the admin.</p>
<img src="/forty-jekyll-theme/assets/images/jeudemots4.png" alt="" data-position="top center" />
<img src="/forty-jekyll-theme/assets/images/jeudemots.png" alt="" data-position="top center" />
<p>Once the game is finished, the players have access to their global and personal scores, as well as the statistics of the game and badges.</p>
<p>The source code is available here : <a href="https://github.com/raphael-hascoet/Jeu-de-mots">https://github.com/raphael-hascoet/Jeu-de-mots</a>.</p>
