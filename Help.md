# Help document for people who are stuck!

You were probably sent here after having pressed the "help" button while trying out PolyGlot Quiz Generator. If you can't find an answer to your problem here, want to report a bug, suggest a feature or contact me for whatever reason, you can create an [issue](https://github.com/Siman-56/PolyGlot-Quizz/issues) or message me at siman_56_34750 on discord.

### I can't upload my file
Make sure you are trying to upload your language file ending in '.pgd'. This is the file read by PolyGlot when you open your language within the app. If you do not know where it is, it's most likely in a file named PolyGlot in your home directory (usualy `/Users/[username]/PolyGlot/` on mac or `C:\Users\[username]\PolyGlot` on windows), along with your error log and font files. Make sure not to move it or you may have trouble opening your language in PolyGlot, you can safely upload it to PolyGlot Quiz Generator from there or copy it to another directory.
Your file must also be a language created in PolyGlot, disk images with the same file extention will not work.

## Question types
#### Local language to conlang
Multiple choice question where you select the conlang translation of a given word in your local language.
#### Conlang to local language
Multiple choice question where you select the local language translation of a given word in your conlang.
#### From definition
Multiple choice question where you are given the long form definition of a word and select the correct conlang word.
#### Guess part of speech
Multiple choice question where you select the correct part of speach of a given conlang word. Text input accepts either the POS name or gloss.
#### Guess lexical class
Multiple choice question where you select the correct lexical class(es) of a given conlang word. If the word has multiple lexical classes, text input accepts one or multiple of them, so long as none are incorrect. If multiple classes are given they should be seperated by a space (`W1 W2`), a comma (`W1, W2`) or a semi-colon (`W1; W2`).
#### From pronounciation
Multiple choice question where you select the conlang word matching the given IPA pronounciation.
#### Guess pronounciation
Multiple choice question where you select the correct IPA notation of a given word.
#### True/False translation
True or false question on whether a given conlang word and local word are equivalent.
#### Phrasebook translation
Multiple choice question where you select the correct translation of a given phrase from your phrasebook.
#### Phrasebook True/False
True or false question on whether a given phrase has been assigned the correct translation.
#### Guess conjugation
Multiple choice question where you select the correct conjugation based on the given parameters
#### Guess inflectional categories
Multiple choice question where you select the correct parameters for a given conjugation of a word. May not work very well if you have a lot of repeated declensions.

## Other settings
#### Answer format
Selecting *Text Input Only* will make all questions described above as multiple choice questions become text input questions. Make sure to enter your answer as it is written in PolyGlot. This will not affect true/false questions. 

Selecting *Both (50/50 chance)* will give each relevant question a 50% chance of being either.
#### Number of choices
Determines number of options each multiple choice question will have. Not visible if you have selected *Text Input Only* on the previous parameter.
#### Reveal answer after wrong guess
This will reveal the correct answer if you get a question wrong.
#### Show word info panel
When selected, a panel showing information about the relevant word will be shown after you confirm your guess. Independant of *Reveal answer after wrong guess*.
#### Case sensitive
When selected, text input will be case sensitive.
#### Accent sensitive
When selected, text input will distinguish between accented letters, like è/é/ë/e, ç/c/ć or î/ï/į/i. If not selected, these letters will be treated as identical.
#### POS sensitive multiple choice
When selected, options in multiple choice questions will all have the same part of speech as the correct answer, especialy usefull for languages with distinctive features associated with certain parts of speech.
