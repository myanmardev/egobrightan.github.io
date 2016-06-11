---
layout: post
title: "How To Get Data From Server"
tags: "REST"
---

API 

Base Link 
>`http://mmsoccer.herokuapp.com`

> `Base`/`standings/424`  ( Euro 2016 Match)

```
links":
{"self":{"href":"http://api.football-data.org/v1/soccerseasons/424/fixtures"},
"soccerseason":{"href":"http://api.football-data.org/v1/soccerseasons/424"}},
"count":35,"fixtures":[
     {"_links":
           {"self":{"href":"http://api.football-data.org/v1/fixtures/149885"},
         "soccerseason":{"href":"http://api.football-data.org/v1/soccerseasons/424"},
        "homeTeam":{"href":"http://api.football-data.org/v1/teams/1065"},
         "awayTeam":{"href":"http://api.football-data.org/v1/teams/788"}},"date":"2016-06-11T13:00:00Z","status":"FINISHED","matchday":1,"homeTeamName":"Albania","awayTeamName":"Switzerland","result":{"goalsHomeTeam":0,"goalsAwayTeam":1,"halfTime":{"goalsHomeTeam":0,"goalsAwayTeam":0}}},{"_links":{"self":{"href":"http://api.football-data.org/v1/fixtures/149861"},"soccerseason":{"href":"http://api.football-data.org/v1/soccerseasons/424"},"homeTeam":{"href":"http://api.football-data.org/v1/teams/833"},"awayTeam":{"href":"http://api.football-data.org/v1/teams/768"}},"date":"2016-06-11T16:00:00Z","status":"IN_PLAY","matchday":1,"homeTeamName":"Wales","awayTeamName":"Slovakia","result":{"goalsHomeTeam":1,"goalsAwayTeam":0}},{"_links":{"self":{"href":"http://api.football-data.org/v1/fixtures/149860"},"soccerseason":{"href":"http://api.football-data.org/v1/soccerseasons/424"},"homeTeam":{"href":"http://api.football-data.org/v1/teams/770"},"awayTeam":{"href":"http://api.football-data.org/v1/teams/808"}}

```