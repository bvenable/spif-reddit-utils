spif-reddit-utils
=================

my reddit utils

prerequisites: Python 2.x and [praw](http://praw.readthedocs.org/)

    pip install praw

some sample usage and output (type any command that needs args without args to get usage)

```
newposts all
1 0 29s5m7 HE-MAN69WOO Mod post to celebrate new subreddit!
1 0 29s5m6 rssr No humans necessary: Computers to take on writing duties at news wire
1 0 29s5m5 psychozombie comp vkp files error again every month.
1 0 29s5m4 Sidicer I have a confession to make..
1 0 29s5m3 prezpwns Beauty of a day out on the Palmer course in Alaska.
1 0 29s5m2 dafunniest Can anyone find more pics of this car?
1 0 29s5m1 Radeon_Killer Found a visual bug with Evelyn.
1 0 29s5m0 Zacrem DRAFT BOARD LUCK!
1 0 29s5lz empty_Dream How really Works All random Deathmatch
1 0 29s5ly Gumby_15 LeBron reps reportedly meeting with possible suitors in Cleveland. Includes Cavs, Mavs, and Suns.
1 0 29s5lx MyNewMoniker So my cousin's triplets celebrated being alive 6-months. They seem to be okay with not getting cake.
1 0 29s5lw idledebonair About Last Night | The Broadway musical crisis
1 0 29s5lv Ratelslangen2 I will be the one to kick off.
1 0 29s5lu cakethulu guitar smells like cat urine
1 0 29s5lt Budget_Raygun Laika the Kitty Travels Beyond the Sun!

viewpost 29s5m6
1 rssr No humans necessary: Computers to take on writing duties at news wire
http://rt.com/usa/170340-computers-ap-article-writing/
http://www.reddit.com/r/test16/comments/29s5m6/no_humans_necessary_computers_to_take_on_writing/

commentpost 29s5m6 "cool"
username [spif]: <cr>
Password: <password><cr>
1 rssr No humans necessary: Computers to take on writing duties at news wire
http://rt.com/usa/170340-computers-ap-article-writing/
adding comment:
cool

./vote 29s5m6 up
username [spif]: <cr>
Password: <password><cr>
1 No humans necessary: Computers to take on writing duties at news wire
1 No humans necessary: Computers to take on writing duties at news wire

```

TODO:
* sort out confirming votes, may not be possible
* password file/cache/use netrc

