# Udacity-Tournament-Database

### Created to meet requirements for project 2 in the [Udacity Full Stack Nanodegree](https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004) program
## Files
* tournament.py: Constructs the swiss tournament rules using DB API to interact with tournamet.sql
* tournament.sql: SQL databases, tables, and views
* tournament_test.py: Minimum test requirements for swiss pairing system.

##Getting Started
### What you need
* Python 2.7.10
* PostgreSQL 9.4.2

### Now What?
* Run `$ python tournament_test.py`

You should see this output:
```
$ python tournament_test.py
1. Old matches can be deleted.
2. Player records can be deleted.
3. After deleting, countPlayers() returns zero.
4. After registering a player, countPlayers() returns 1.
5. Players can be registered and deleted.
6. Newly registered players appear in the standings with no matches.
7. After a match, players have updated standings.
8. After one match, players with one win are paired.
Success!  All tests pass!
```
