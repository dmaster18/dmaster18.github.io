---
layout: post
title:      "The Word Unscrambler App (Final)"
date:       2021-01-10 20:26:07 +0000
permalink:  the_word_unscrambler_app_final
---

The Word Unscrambler is a game based on the JavaScript React framework. It allows users to play a game where they are tasked with generating as many words as possible from a random grouping of nine letters.

## Installation

The Word Unscrambler can be downloaded from https://github.com/dmaster18/The-Word-Unscrambler-App. Once the program is downloaded, go to the program's 'backend' directory from your local Terminal/Command Line and then run bundle install or bundle exec install to ensure all the dependencies are installed. Once all the backend dependencies have been installed and deals have been created, run the rails s command from your machine to run the rails server.

In a separate Terminal window, go to the program's 'frontend' directory. Run npm install to install all the necessary JavaScript and React dependencies. Once complete, run npm start and you will be sent to the program's homepage on your default web browser.

## Usage

From the homepage, the user can click links to either play a short, medium, or long game,  or he or she can feel free to visit the Word Trainer to buff up his or her vocabulary.

In all the game modules, the user must score as many points as possible by creating as many words in the allotted time. Each word has a score that is equivalent to the length of the word, so a two-letter word is worth two points and a nine-letter word is worth nine points.

In the short word game, the user must score as many points as possible within a minute from one letter grouping. Likewise, in the medium and long word games, the user must do the same but with five and ten possible letter groups within three and five minutes, respectively. The user cannot use any letter tile more than once when forming a new word. When a user enters a word, the game will inform him whether the word is correct or not. Upon completion of any of the games, the use will be given his or her final score. If proud of the final score, the user can choose to submit the score along with his or her name to the app's leaderboard, which will showcase the score to the whole world.

In addition to the short, medium, and long game modules, a user can choose to visit the app's leaderboard that shows all the submitted players' names and corresponding scores. Lastly, there is also a 'Word Trainer' component that allows the user to view all the different two- through nine-letter possible word combinations that can be formed from all of the app's nine-letter pairings. This can both help the user improve his or her final score as well as improve his or her vocabulary. Each word is a link that, when clicked, leads to the word's definition on Dictionary.com. 

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/dmaster18/The_Word_Unscrambler_App/pulls. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

