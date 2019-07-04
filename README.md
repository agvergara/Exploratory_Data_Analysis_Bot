# Exploratory_Data_Analysis_Bot

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/agvergara/Exploratory_Data_Analysis_Bot/blob/master/cunhaobot_stats.ipynb)

Data Analysis for a Bot in Telegram

(This is a Spanish bot in Telegram, you can summon it with @cunhaobot)

Sure you know about brothers-in-law, right? In Spain we call them "cuñados" but they are not only brothers-in-law, but a well of wisdom in the spanish culture and also well versed in numerous topics such as:
* Politics
* Life
* Relationships
* Science
* General culture
* Geography
* And a long etcetera

Well this is an exploratory analysis (mainly to train myself on the visualization of data with matplotlib and pandas) about the uses of the bot in general and user by user.

---

### Bot Usage

At the time of this commit, there are only:

* How many unique users (not groups yet) are using this group and how many features I extracted from the data.
* Count of bots using the bot (all should be False as no bot is using this bot, so the "Maybe" category in fact is a NaN as the field doesn't exist in the data, it's just for giggles)
* How many times the bot has been used in the main categories/queries:
  * _corta_ : Short phrase
  * _larga_ / _largo_ / _long_ / _frase_ : Long phrase
  * _audio_ / _sonido_ : Audio clip as in _text-to-speech_ just translate a long phrase into an audio clip
  * _help_ / _ayuda_ : Help of the bot
  * _mal_ : Bad use of the bot

* Personal use of the bot, search by user:
  * How many times the particular user has used the bot and with what query
  * Total count of times this particular user has used the bot

* Search query: Searches the query and outputs the stats (if verbose) of every user that used that specific query.


Aaaand for now that's all folks
