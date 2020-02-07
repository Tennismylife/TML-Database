# TML-Database
A complete and live updated Database with ATP tournaments matches tested many many times by the scripts to search tweeted records and stats https://twitter.com/TennisMyLife68

This work is based on Sackmann one (all rights reserved) available at this link https://github.com/JeffSackmann/tennis_atp it were mantained the same patterns in columns order for a better compatibility. But using Sackmann csvs we will find many missing data. i.e. the famous 1274 winning matches in Connors' career all avaible in our Database and not in Sackmann one, and many other examples.

The columns are*
* tourney_id = this is tournament id based on ATP database

* tourney_name = name of the city of the played tournament

* surface = hard, clay, grass, carpet

* draw_size = 128, 64, 32, 16, 8, 4

* tourney_level = G (Grand Slam), 'A' (ATP Tour), 'D' (Davis Cup), 'F' (Masters / ATP Finals)

* tourney_date = week of the tournament

* match_num = 

* winner_id = winner id based on ATP players database

* winner_seed = 1,2....32 based on draw seed

* winner_entry = Q, WC, LL, SE

* winner_name = Name + Surname

* winner_hand = R (Right), L (Left)

* winner_ht = heigth

* winner_ioc = nazionality

* winner_age = age in yy.yy format

* winner_rank = ranking based on ATP rankings database

* winner_rank_points = ranking points based on ATP rankings database

* loser_id = v. winner_id

* loser_seed = v. winner_seed

* loser_entry = v. winner_entry

* loser_name = v. winner_name

* loser_hand = v. winner_hand

* loser_ht = v. winner_ht

* loser_ioc = v. winner_ioc 

* loser_age = v. winner_age

* loser_rank = v. winner_rank

* loser_rank_points = v. winner_rank_points

* score = score of the match

* best_of = 3 or 5

* round = R128, R64, R32, R16, QF, SF, F 

* minutes = match duration

* w_ace = winner aces

* w_df = winner double faults

* w_svpt = winner service points

* w_1stIn = winner 1st serve in

* w_1stWon = winner 1st serve won

* w_2ndWon = winner 2nd serve won

* w_SvGms = winner service games

* w_bpSaved = winner saved break points

* w_bpFaced = winner faced break points

* l_ace = loser aces

* l_df = loser double faults

* l_svpt = loser service points

* l_1stIn = loser 1st serve in

* l_1stWon = loser 1st serve won

* l_2ndWon = loser 2nd serve won

* l_SvGms = loser service games

* l_bpSaved = loser saved break points

* l_bpFaced = loser faced break points

There will be a constant checking on ATP database addition, removing, fixing etc. So as additions from newspapers, blog and tennis statistics website.

There will be a live results update based on current ATP Matches so the stats and the records will be always updated not only on Monday as we can see on ATP website

For a better quality the users can report eventual bugs, missing data and other errors

A significant different with Sackmann database is using ATP players id for a more confortable methods to calculate records and searching data on ATP website
