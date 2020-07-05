<h1 style="font-weight:normal" align="center">
  Will Sutton's House of Games 
</h1>

<div align="center">

Inspired by the BBC TV programme [Richard Osman's House of Games](https://www.bbc.co.uk/programmes/b094mjv0) this a recreation of some of the quiz rounds packaged up in an R shiny app. 

:construction: Repo Under Construction :construction: 

Work in Progress Version of Quiz available here:  [https://wjsutton.shinyapps.io/house_of_games_wip/](https://wjsutton.shinyapps.io/house_of_games_wip/)

[Twitter][Twitter] :speech_balloon:&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[LinkedIn][LinkedIn] :necktie:&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[GitHub :octocat:][GitHub]&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;[Website][Website] :link:

</div>

<!--
Quick Link 
-->

[Twitter]:https://twitter.com/WJSutton12
[LinkedIn]:https://www.linkedin.com/in/will-sutton-14711627/
[GitHub]:https://github.com/wjsutton
[Website]:https://wjsutton.github.io/

### :monocle: About

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

#### :thinking: Round 1: TO DO

[] Automate finding of popular movie quotes
[] Automate finding of similar films
[] Automate rewording of quotes

### :thinking: TO DO

[] Automate Round 1 questions
[] Find different types of games for future round
[] Figure out which rounds are achieveable in learnr package/shiny app environment
[] Restyle UI




