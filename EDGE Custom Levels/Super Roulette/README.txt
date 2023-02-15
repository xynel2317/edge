How do I install the level?

1. Download the files
2. Open Steam
3. Right click EDGE
4. Click Properties > Local Files > Browse
5. Open the "music" folder and drag "04_Jingle.ogg" from the repository to there
6. Go back and open the "models" folder and drag "CAA8AD0F050DB82A.eso" from the repository to there
7. Go back and open the "levels folder and drag "super_roulette.bin" from the repository to there
8. Edit mapping.xml in the "levels" folder.
9. Search </standard>, </extended> or </bonus> and paste the following string behind the text you searched:

<level filename="super_roulette" leaderboard_id="70557" name_sfx="super_roulette"/>

10. Save the file
Enjoy the level!

If it wasn't obvious enough, pasting it behind </standard> will add the level to "normal levels", pasting it behind </extended> will add the level to "extended levels" and pasting it behind </bonus> will add the level to "bonus levels"
