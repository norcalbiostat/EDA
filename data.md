# Baseball Project

[Slack discussion board](https://ids-f17.slack.com/messages/C79AVRG0J/convo/C79AVRG0J-1506553717.000204/)

## Location of important Variables that we will be using throughout this project

## Created Variables not in tables

* **OPS:** On base percentage plus slugging. 

* **OBP** On base percentage. Calculated (Hits + Walks + Hit by Pitch) / (At Bats + Walks + Hit by Pitch + Sacrifice Flies

* **SLG** Slugging Calculated by total bases divided by at bats

## Variables in all tables needed to link with each other

* **PlayerID:** A unique code asssigned to each player.The playerID links the data in this file with records in the other files.

* **yearID:** Year

## MASTER: Player names, DOB, and biographical info

* **nameFirst:** Player's first name

* **nameLast:** Player's last name

## Batting Table

* **teamID:** Team

* **G:** Games

* **H:** Hits

* **2B:** Doubles

* **3B:** Triples

* **HR:** Homeruns

* **SQ:** Strikeouts

* **GIDP:** Grounded into double plays

## Pitching table

* **teamID:** Team

* **W:** Wins

* **L:** Losses

* **G:** Games

* **H:** Hits

* **HR:** Homeruns

* **SO:** Strikeouts

* **ERA:** Earned run Average

* **SH:** Sacrifices by opposing batters

* **SF:** Sacrifice flies by opposing batters

* **GIDP:** Grounded into double plays by opposing batter

## Fielding Table

* **teamID:** Team

* **G:** Games

* **Dp:** Double plays

## Hall of Fame Table

* **playerID:** Player ID Code

## PitchingPost Table

* **teamID:** Team

* **G:** Games

* **yearID:** Year

* **H:** Hits

* **HR:** Homeruns

* **SO:** Strikeouts

* **ERA:** Earned run Average

* **SH:** Sacrifices by opposing batters

* **SF:** Sacrifice flies by opposing batters

* **GIDP:** Grounded into double plays by opposing batter

## BattingPost Table

* **teamID:** Team

* **G:** Games

* **H:** Hits

* **2B:** Doubles

* **3B:** Triples

* **HR:** Homeruns

* **SQ:** Strikeouts

* **GIDP:** Grounded into double plays

## Salaries Table

* **teamID:** Team

* **salary:** Salary