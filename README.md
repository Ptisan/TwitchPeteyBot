# TwitchPeteyRobot ("PtRobot")
A personable moderation bot for my Twitch channel.  It functions less like a machine and more like a person.

I dislike most other popular Twitch.tv chat moderation bots due to their very machine-like functionality and responses.  My goal with this project is to have a robotic IRC moderator that has a basic, yet personable, character.

First, rather than addressing the bot's chat command functions with '!\<command\>', PeteyRobot should use the modern way of tagging other social media users with '@\<username\>, \<command\>' or '\<command\>, @\<username\>'.  Although verbose, this forces a chat user to see PeteyRobot as another chat user, not a machine.  Ultimately, order should not matter (as it does not in the English language), but the bot should be addressed to know you are speaking to it.  There are few scenarios when PeteyRobot will speak up without being addressed as part of it's moderation duties.  Examples of this behavior would be letting a user know that I have been sent an alert when I have been addressed in chat or notifying a user of why their behavior has warranted a disciplinary action.

Second, PeteyRobot should never have just one dictionary response for any given command.  If I ask a human the same question over and over, although they may be annoyed, I would never expect to recieve the exactly-worded same answer twice.  I am programming PeteyRobot with a basic AI brain in order to provide multiple different ways to respond to a dictionary of questions.  The goal of this is that PeteyRobot will be able to respond, any time it is addressed, with a varying catalog of responses.

On a grand scale, PeteyRobot would eventually evolve into the Cortana/Siri of Twitch/IRC.

PeteyRobot is loosely based on BadNidalee's ChatBot (https://github.com/BadNidalee/ChatBot) and cormac-obrien's twitchbot (https://github.com/cormac-obrien/twitchbot).  It is being written in Python 2 and, should it become popular enough, perhaps will port to Python 3.
