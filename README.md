# TV shows recommendation

Final project for the Building AI course

## Summary

The goal of the project is to deliver a solution that would use different AI methods which would help to discover and suggest TV shows to the user based on his/her viewing history across different streaming platforms and TV showtime tracker application.


## Background

I am a big fan of TV shows of different genres, length, original language, ... and when searching for another TV show to watch I am spending quite a lot of time to find the right recommendations from which I could choose. This problem occurs couple of time a month.

The problems I am facing when doing manual research and selections are:
* its time consuming
* non-mainstream shows are not shown in general recommendations
* foreign TV shows are less likely to appear in general recommendations

This recommendation solution would take person's viewving history and do the analysis of that based on following criteria:
- genre
- length
- language
- main characters
- user's recent history

After analysis would be done, using the database of existing TV shows a recommendation would be provided to the user. Watching habits and taste of the user are changing over time and the same applies for the recommendations, that would be adapting as the viewving history and habit in the recent past of the user has changed.

Each of the criteria would have its own weight when creating the recommendation list.

## How is it used?

The tool would be used either as a web-based application or a mobile application. 
At the start users would fill out some basics about their likes and dislikes in regards to the TV shows. For this application user will have to provide access to different streaming platforms and applications. The reason for that is that the application needs a source from where it can learn the user's viewing preferences.

## Data sources and AI methods

There are following sources of data:
- data filled out by the user
- data extracted from applications used by the user
- IMDB data

Data from 3rd party applications:
- streaming platforms (Netflix, HBO, Apple, Disney, ...)
- tracking applications (e.g. TV Time)

There are multiple APIs available for that such as:
- Netflix API, IMDb API, AppleTV API, ...
- Guidebox API (indexes all streaming platforms)

## Challenges

The challenge would be in consolidating all the sources into one data source over which AI methods can be used.
Data privacy of the users and their preferences.


## What next?

Implemnenting this as a plugin into different TV tracker applications or the Smart TV itself.
