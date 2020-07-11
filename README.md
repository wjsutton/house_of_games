<h1 style="font-weight:normal">
  Will Sutton's House of Games 
</h1>


[![Status](https://www.repostatus.org/badges/latest/wip.svg)]() [![GitHub Issues](https://img.shields.io/github/issues/wjsutton/house_of_games.svg)](https://github.com/wjsutton/house_of_games/issues) [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/wjsutton/house_of_games.svg)](https://github.com/wjsutton/house_of_games/pulls) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

Inspired by the BBC TV programme [Richard Osman's House of Games](https://www.bbc.co.uk/programmes/b094mjv0) this a recreation of some of the quiz rounds packaged up in an R shiny app. 

:construction: Repo Under Construction :construction: 

Work in Progress Version of Quiz available here:  [https://wjsutton.shinyapps.io/house_of_games/](https://wjsutton.shinyapps.io/house_of_games/)

[Twitter][Twitter] :speech_balloon:&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[LinkedIn][LinkedIn] :necktie:&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[GitHub :octocat:][GitHub]&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[Website][Website] :link:


<!--
Quick Link 
-->

[Twitter]:https://twitter.com/WJSutton12
[LinkedIn]:https://www.linkedin.com/in/will-sutton-14711627/
[GitHub]:https://github.com/wjsutton
[Website]:https://wjsutton.github.io/

### :a: About

This a the working space for a shiny app that recreates a [Richard Osman's House of Games](https://www.bbc.co.uk/programmes/b094mjv0)  style quiz.

### :checkered_flag: Getting Started

The project is built using R version 3.6.2 and uses the RStudio IDE to build and deloy the shiny app.

```
install.packages("learnr")
library(learnr)

# If you've never used/seen learnr before view tutorial here:
learnr::run_tutorial("hello",package = "learnr")
```

### The Quiz

#### Round 1: Movie Quote Thesaurus

*Here's a quote from a popular film, we've reworded the quote - can you name the film?*

This data is drawn from the file: `movie_quotes.csv` for listing out 10 reworded quotes. Creation of `movie_quotes.csv` is currently manual with the steps identified as:

- Find popular movie quotes.
- Find similar movies by: year of release, genre, actors, etc.
- Reword original quote replaced with synonyms but ensure the quote is still understandable.

These tasks can be automated with some data work, e.g. using IMDB to find quotes and similar movies. Tests of using the syn R package shows too many synonyms and often the meaning of the quote is completely lost.

#### Round 1: 

- [ ] Automate finding of popular movie quotes
- [ ] Automate finding of similar films
- [ ] Automate rewording of quotes

### :thinking: TO DO Lists:

#### Round 1

- [ ] Automate finding of popular movie quotes
- [ ] Automate finding of similar films
- [ ] Automate rewording of quotes

#### General

- [ ] Find different types of games for future round
- [ ] Figure out which rounds are achieveable in learnr package/shiny app environment
- [x] Restyle UI

#### Test Other Games

- [ ] Where is Kazakhstan -> answer to a question is a point on a map, pick a point on a the map
- [ ] Answer Smash -> picture from a theme (e.g. tools) and answer to a question smash together to form 1 answer, e.g. picture of a Hammer + "Underwater Disney adventure about this little humanoid creature" = Hammermaid (Hammer + Mermaid)
- [ ] Broken Karaoke -> the first letter of each word from the lyrics of a popular song appear on screen in the rythme of the song
- [ ] Games of House -> questions but in reverse - with answers in reverse too

