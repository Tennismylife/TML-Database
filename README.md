# TML-Database
A complete and live updated Database with ATP tournaments matches
tested many many times by the scripts to search tweeted records and
stats https://twitter.com/TennisMyLife68

This work was originally based on Jeff Sackmann's (available at
https://github.com/JeffSackmann/tennis_atp under Creative Common Non
Commecial Share Alike). We therefore mantained the same patterns in
column names and ordering. However, using Sackmann's csvs we
encountered many missing data which we proceeded to integrate. As an
example, the famous 1274 won matches in Connors' career are all
present in our Database and not in Jeff's. There are many other
examples, too many to list them all here. Another significant
difference with Sackmann's database is using ATP's players id for a
more confortable method to calculate records and searching data on ATP
website.

The columns are:

* tourney_id = tournament id based on ATP database

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

We constantly check ATP additions, removals and fixings of historical
records from their database. We keep integrating these data with own
additions from newspapers, blogs and tennis statistics websites.

Our database will be frequently updated, daily or even more often,
ideally following live results of ATP Matches: we don't want to wait
till next Monday to compute interesting statistics!

We are open and thankful for collaborations and reporting of eventual
bugs, missing data and other errors: we all want to improve the
quality of this database.

Enjoy!


This database is offered in partnership with https://canaltenis.com/


![Image description](https://pbs.twimg.com/profile_images/1150124885148086273/MLggdMOo_400x400.png)
