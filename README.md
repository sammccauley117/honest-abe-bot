<p align="center">
 <img src="misc/honest-abe-round.png" width="300">
</p>

# Honest Abe
Honest Abe is an automated Twitter robot that attempts to expose hypocritical U.S. politicians that accept ~~bribes~~ donations. He is built on Python, implements the Tweepy Twitter library, and makes use of basic sentiment analysis tools. Honest Abe scans politician's tweets and looks for political keywords. After picking out keywords, he associates them with a given industry. He then cross-references this industry with the [OpenSecrets](https://www.opensecrets.org/) political donation database to see if the politician receives donations from the industry. For example, if Senator Mitch McConnell tweets about gun control, Honest Abe will flag the word 'gun', associate that with the firearm industry, and then cross-reference the database. When Abe finds that Senator McConnell has received millions from the firearm industry, he will reply to the Senator's tweet calling him out on this conflict of interest. Honest Abe's Twitter can be viewed at the Twitter handle [@HonestAbeBot](https://twitter.com/honestabebot).

## Issues
The biggest problem with Honest Abe is false flags. There are times when a politician actually does the right thing and goes against their donor's interests, yet Honest Abe will still 'expose' them. Initially, roughly 25% of Abe's replies were false flags. This rate was improved by implementing sentiment analysis tools that were used to try and predict whether or not the politician was going against the donor's interest. Though the sentiment analysis tools reduced false flags, they are still common. I also believe the sentiment analysis tools added bias to Abe, something that I don't think is ethical or fair. Honest Abe is not currently operating due to the false flags—the last thing we need is *more* misinformation in politics. 
