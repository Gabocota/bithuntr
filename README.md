# bithuntr
A simple text-based captcha to protect the internet against GPT and other bots.

A few months ago, I was fooling around with Chat-GPT and I realized that it has a very poor understanding of letters in words.

<img src="https://github.com/Gabocota/bithuntr/assets/88735758/555c8055-98a6-4c01-b9bb-c7ef400d3c8f" height="200px">

<img src="https://github.com/Gabocota/bithuntr/assets/88735758/60151c07-029c-48f4-a41f-ca27984284f6" height="200px">

After playing around with it for a while I got bored and went to do something else. But weeks later I realized the potential of this. This is something very simple that anybody can do but the smartest text ai can’t, this means we can use it as a filter.
You may say you can just write some simple code to count the number of apparitions of a letter in a word:
```var len = word.split(char).length - 1```
To prevent this the user is prompted with different wording every time.

<img src="https://github.com/Gabocota/bithuntr/assets/88735758/b70c26d2-1f6d-4075-8787-c4e083371a7e" height="100px">

<img src="https://github.com/Gabocota/bithuntr/assets/88735758/72f0a335-e3c8-4792-b23d-e5d90ecec5bd" height="100px">

<img src="https://github.com/Gabocota/bithuntr/assets/88735758/e7aad896-23ef-4ccc-8d81-59069d81f7e8" height="100px">

This makes it almost impossible to code a script to obtain the actual problem parts.

It is true that Chat-GPT isn't totally useless and sometimes it does get it right. To go around this every word in the word list was first checked to make sure GPT gets it wrong the overwhelmingly majority of time.

<img src="https://github.com/Gabocota/bithuntr/assets/88735758/50358df4-a4d9-4387-a212-b6772e69d2f5" height="200px">

