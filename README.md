# FightHoax Artificial Intelligence Fact-Checking Tests

[FightHoax](http://fighthoax.com/) is an algorithm built by developer Valentine Tzekas. It classifies ingested links to articles as either “Trusted,” “Hoax,” or “Mixed” based on seven different criteria, ranging from language quality to author’s publication history.

I got access to the FightHoax API private beta in mid 2017 and ran two tests to check the algorithms performance. I'm uploading the raw results for inspection here.

For testing FightHoax I used two lists of news items: one from BuzzFeed’s Craig Silverman with items that had been already flagged as fake or accurate; I called that list as 'legacy news items'. The second list I compiled it myself with items published on the day of my test. I called that list 'current news items.'

[BuzzFeed’s Craig Silverman list from November 2016](https://docs.google.com/spreadsheets/d/1ysnzawW6pDGBEqbXqeYuzWa7Rx2mQUip6CXUUUk4jIk/edit) was used to show how much more engagement (reactions, shares and comments) fake or false news items are gaining on Facebook comparing to real news. For current (possibly) fake news, I compiled a list of 95 articles from both legitimate news sources, websites that have been accused in the past for publishing fake or false stories, as well as websites publishing outright satire or hoaxes.
On some stories that were linking to online sources to a different website, the source link was added to the list in order to test algorithm performance between the two versions of the story. 

FightHoax overall performed with decent accuracy when it came to news items that had been proved fake, but experienced several inconsistencies when it tried to identify news published on the day of the test.
