# Building a Karma Bot with Python and the Slack API 

![karma avatar](https://user-images.githubusercontent.com/24620154/56662126-952d7f00-66a3-11e9-99b4-924dc6313b2e.png)

[![BCH compliance](https://bettercodehub.com/edge/badge/pybites/karmabot?branch=master)](https://bettercodehub.com/)

Inspiration: [hipchat](https://blog.hipchat.com/2016/05/02/meet-karma-bot/) // actively serving our [PyBites Slack Community](https://pybit.es/pages/community.html)

PyBites Article: [From Script to Project part 1. - Building a Karma Bot with Python and the Slack API](https://pybit.es/slack-karma-bot.html)

![karma example](https://pybit.es/images/karma_example.png)

__Update 06.09.2018__: karmabot now supports commands, add them to the `commands/` subdirectory, then import it to `bot/slack.py` and add it to `BOT_COMMANDS`. More info: https://www.youtube.com/watch?v=Yx9qYl6lmzM&amp;t=2s

__Update 01.11.2018__: depending the type of commands you contribute, we merge it into master (= @karmabot revision used on our Slack). For more general purpose commands, not directly relevant to our @karmabot / Slack community, we made a [_utils_ branch](https://github.com/pybites/karmabot/tree/utils). We will merge those type of commands into that branch. 
