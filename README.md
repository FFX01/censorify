#Censorify

To add words to the custom censored words lists call the addCensoredWord(arg) and pass in the word you would like censored as an argument. Please only pass in one word at a time in string format as the application can not handle anything else at the moment.

To see a list of all censored words, simply call the getCensoredWords() function with no arguments.

To censor a string simply pass it to the censor() function as an argument and all words that match words found in the list of censored words will be censored to '***'.
