![AgeOfNRecord](http://www.tennismylife.org/wp-content/uploads/2015/09/cropped-header.jpg)

# TML-Database – Complete Live ATP Match Database

[Explore stats.tennismylife.org](https://stats.tennismylife.org/) – a dedicated website to explore **live and historical ATP match data**, including player stats, tournament results, and rankings.

Follow updates on Twitter: [@TennisMyLife68](https://twitter.com/TennisMyLife68)

# ⚠️ NOTICE: DATABASE NOW AVAILABLE ON TML

🚀 The **TML-Database** has been **fully moved to our official website** to provide **live access, continuous updates, and an interactive experience**:  

👉 TML Tennis Match Database: [https://stats.tennismylife.org/tennis-match-database](https://stats.tennismylife.org/tennis-match-database)


Here you will find:  
- All **historical and live-updated ATP match data**  
- Complete statistics on players and tournaments  
- Advanced filters for exploring records and customized stats  

💡 This GitHub repository is now kept only for **historical reference and technical purposes**, but **all features and the fully updated database are available on the website**.


---

## ⚠️ Important Notice

This database contains **ATP match data, player statistics, and historical records**. All data is collected and maintained with care, but it is intended for **educational, analytical, and research purposes only**.  

Please note:  

- All ATP player IDs, match results, and tournament information are based on the official ATP website.  
- Redistribution, commercial use, or selling of the raw database without permission from TennisMyLife and/or the ATP may violate copyright or terms of use.  
- The database is **frequently updated**, but errors or missing data may exist. Use at your own discretion.  
- Collaborations, bug reports, and data contributions are **welcome and appreciated**.  

By using this repository, you agree to respect these conditions and acknowledge the sources of the data.

---

## Overview

This repository contains a **complete and live-updated database of ATP tournaments and matches**, originally inspired by Jeff Sackmann's [tennis_atp repository](https://github.com/JeffSackmann/tennis_atp) under **Creative Commons Non-Commercial Share Alike**.  

Key differences from Sackmann’s database:  

- All missing data in Sackmann’s CSVs have been integrated. For example, **Connors’ 1274 career wins** are fully included here.  
- **ATP player IDs** are used for easier cross-referencing, record calculation, and data search on the ATP website.  
- Data is continuously checked and updated using ATP official additions and corrections, as well as supplementary sources like newspapers, blogs, and tennis statistics websites.  

The database is **updated daily or more frequently**, ideally following live results.

---

## Database Columns

| Column | Description |
|--------|-------------|
| tourney_id | Tournament ID (ATP database) |
| tourney_name | City of the tournament |
| surface | Surface type: hard, clay, grass, carpet |
| draw_size | 128, 64, 32, 16, 8, 4 |
| tourney_level | G (Grand Slam), A (ATP Tour), D (Davis Cup), F (Masters / ATP Finals) |
| tourney_date | Week of the tournament |
| match_num | Match number |
| winner_id | Winner ATP ID |
| winner_seed | Seed of the winner (1–32) |
| winner_entry | Q, WC, LL, SE |
| winner_name | Full name of the winner |
| winner_hand | R (Right), L (Left) |
| winner_ht | Height (cm) |
| winner_ioc | Nationality (IOC code) |
| winner_age | Age in yy.yy format |
| winner_rank | ATP ranking at match time |
| winner_rank_points | ATP ranking points at match time |
| loser_id | Loser ATP ID |
| loser_seed | Seed of the loser |
| loser_entry | Q, WC, LL, SE |
| loser_name | Full name of the loser |
| loser_hand | R/L |
| loser_ht | Height (cm) |
| loser_ioc | Nationality |
| loser_age | Age |
| loser_rank | ATP ranking |
| loser_rank_points | ATP ranking points |
| score | Match score |
| best_of | 3 or 5 sets |
| round | R128, R64, R32, R16, QF, SF, F |
| minutes | Match duration |
| w_ace | Winner aces |
| w_df | Winner double faults |
| w_svpt | Winner service points |
| w_1stIn | Winner first serve in |
| w_1stWon | Winner first serve won |
| w_2ndWon | Winner second serve won |
| w_SvGms | Winner service games |
| w_bpSaved | Winner break points saved |
| w_bpFaced | Winner break points faced |
| l_ace | Loser aces |
| l_df | Loser double faults |
| l_svpt | Loser service points |
| l_1stIn | Loser first serve in |
| l_1stWon | Loser first serve won |
| l_2ndWon | Loser second serve won |
| l_SvGms | Loser service games |
| l_bpSaved | Loser break points saved |
| l_bpFaced | Loser break points faced |

---

## 2025 Database Reset

Due to high demand, a **full reset** of the database was performed in 2025, including:  

- **Re-scraping all ATP tournaments** from 1968 to 2025, using ATP IDs.  
- **Creation of a supporting player database** with ATP IDs (`ATP_Database.csv`).  
- **Scraping all ATP rankings** and historical rankings (1973–1984). See details [here](https://github.com/Tennismylife/TML-Rankings-Database).  
- **Reset of debugging scripts** and their execution, available [here](https://github.com/Tennismylife/Tennis-R-ecord-Debugger).  

This effectively represents a **new, fully corrected and updated database**.

---

## Contributions

We welcome contributions and bug reports:  

- Missing or incorrect data  
- Enhancements or new features  
- Scripts for data parsing and analysis  

Please submit issues or pull requests in this repository. Together we can improve **TennisMyLife Database**.

---

## License & Credits

- Based on Jeff Sackmann’s work: [tennis_atp](https://github.com/JeffSackmann/tennis_atp)  
- Data collected from **ATP official website**, newspapers, blogs, and other tennis stats sites.  
- Database offered in partnership with [CanalTenis](https://canaltenis.com/).  

All data usage is **non-commercial** unless explicitly permitted.

---

![AgeOfNRecord](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDyydzNXDVdbyxCz1sET3rQ1bj0TDUnKSSDQ&s)
