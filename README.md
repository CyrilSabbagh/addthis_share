addthis_share
=============

Implementing Addthis social share buttons and Smart Layers on your Elgg 1.8 website

This Plugin uses AddThis sharing tools to implement third-party buttons like Google+1, Tweet and Facebook Like. AddThis is the global leader for sharing and social insights.

Features:

Complete share buttons (more than 300 bookmark and share buttons available)
3 styles of button groups to choose
Adjust to display left aligned or right aligned
Updated Addthis-share API version
Smart Layers integration (Follow, Share and what's next)
In order to link the follow buttons to your social profiles just open the file below:

addthis_share/views/default/addthis_share/follow.php

Then in the following code replace [REPLACE WITH YOUR ID] with you profile account id:

{'service': 'facebook', 'id': '[REPLACE WITH YOUR ID]'}, {'service': 'twitter', 'id': '[REPLACE WITH YOUR ID]'}, {'service': 'youtube', 'id': '[REPLACE WITH YOUR ID]'}, {'service': 'instagram', 'id': '[REPLACE WITH YOUR ID]'}

Note that you can add or remove any service you want.

This is my first contribution i have lot more to come RECOMMEND if you like!
Release Notes:
Fixed the settings parameters not responding.

