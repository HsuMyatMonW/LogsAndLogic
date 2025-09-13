# The Password Game

If you've been keeping up with the Internet for the past few years, chances are that you might have come across "[The Password Game](https://neal.fun/password-game/)." It's a browser puzzle game created by Neal Agarwal.

The premise of the game is simple: create a password that follows all the given rules. This may seem easy at first since the game starts off with pretty standard rules that you'd expect in a regular password policy. However, the rules become increasingly strange and complicated as the game goes on, and everything quickly escalates into a wonderful chaotic mess.

The Password Game first came into my knowledge about a year ago and immediately piqued my interest. I played the game for myself, but I only made it to Rule 24 out of a total of 35 rules. Between the constant maintenance required for Rule 23 and the search for a suitable answer to Rule 24, I was unable to split my attention between the two. After several failed attempts, I eventually gave up. 

That was until a month ago, when I stumbled upon a [video](https://youtu.be/-osyW_rpoQs?si=ac6onb_5X4Ck7H-G) explaining the strategies and [resources](https://drive.google.com/file/d/12A2Og_CD6IMQMwbWyb3tLVW0AAmLHG7g/view?usp=drivesdk) that speedrunners use to beat the game in seconds. That's when I realised that I could follow some of these strategies to beat the game myself. So, I finally decided to attempt the game once again, but this time, I was determined to beat it.

## Gameplay

The player is given an input text field with the prompt: "Please choose a password." Once the player starts typing a password, the game introduces the first password rule. When the player enters a password that complies with this rule, the game reveals the second rule, and so on.

To progress, the player must choose a password that satisfies the current rule as well as all previously introduced rules. At times, attempting to follow a new rule may cause the password to break a previous one. In such cases, the player must revise the password to meet all rules up to that point.

There are a total of 35 rules that the final password must satisfy.

## Solving The Puzzle: Rule-By-Rule

### Rule 1: Your password must be at least 5 characters.
This part is easy. I also know that I’ll need to include a month in the password for a later rule based on my previous failed attempts, so I put "April."

### Rule 2: Your password must include a number.
I added "1" to the end of the password. Simple!

### Rule 3: Your password must include an uppercase letter.
The "A" in "April" is already capitalized, so it passes automatically.

### Rule 4: Your password must include a special character.
I added "!" to the end of the password.

### Rule 5: The digits in your password must add up to 25.
There's already a "1" in our password at this point, so I did some quick math and added "45555" to the end of the password.
> 1 + 4 + 5 + 5 + 5 + 5 = 25

### Rule 6: The password must include a month of the year.
I pre-solved this in Rule 1.

### Rule 7: Your password must include a roman numeral.
I added "XXXV" to the end of the password. I chose this specific number because I know the Roman numerals will need to multiply to 35 for a later rule.
> XXXV = 35

### Rule 8: Your password must include one of our sponsors: 🥤☕︎⛽
This rule tells us to include the name of one of the sponsors given. Out of the three choices Pepsi, Starbucks, and Shell, I chose Shell for no particular reason. I added "shell" to the end of the password.

### Rule 9: The roman numerals in your password should multiply to 35.
I pre-solved this in Rule 7.

### Rule 10: Your password must inlcude this CAPTCHA: 🔡
This rule tells us to include the response to the text-based CAPTCHA. Rule 5 states that all the digits in the password must add up to 25, so I was reluctant to add more numbers. I reloaded the CAPTCHA until I got one without any numbers. I added the CAPTCHA response "ebcbx" to the end of the password.

### Rule 11: Your password must include today's Wordle answer.
I paid a quick visit to The New York Times website to play Wordle. I played the game on 01 September 2025. The Wordle answer that day was "LEAST." I added "least" to the end of the password.

### Rule 12: Your password must include a two letter symbol from the periodic table.
I know that sodium is "Na" off the top of my head, so I added "Na" to the end of the password.

### Rule 13: Your password must include the current phase of the moon as an emoji.
I’ve always had trouble finding out the current phase of the moon. Different meteorological websites I checked often have conflicting answers, so I ended up brute-forcing this rule. I added the moon phase emojis one by one until I got it right.

### Rule 14: Your password must include the name of this country. 🗺️📍
This rule tells us to include the country given in the Google Street View / GeoGuessr. I'm not particularly good at GeoGuessr, so it took me quite a bit of scrolling and looking around until I found a sign that confirmed it was Ghana. I added "Ghana" to the end of the password.

### Rule 15: Your password must include a leap year.
Although the year "00" technically does not exist in Gregorian calendar, the game treat it as a leap year. I presume it’s because the program checks if a number is a leap year using the modulo operator. In any case, I added "00" to the end of the password.
> 💡 Including smaller numbers in the password helps keep it simple and reduces the likelihood of failure in later steps.
