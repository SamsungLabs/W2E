---
layout: page
title: What is W2E?
permalink: /about/
---
![W2E]({{ site.baseurl }}assets/W2E.png)  

W2E is a word based cybersecurity event detection system from tweets.  
It detects events based on two types of words.  
1. New words  
The words that have not been seen before the time of event detection.
2. Re-emerging words  
The words that have appeared at least once before the time of event detection, but show a significant rise in their frequencies at the time of detection.
  
For detailed explanation about dictionaries and algorithms of W2E, please check our paper **"[Cybersecurity Event Detection with New and Re-emerging Words](https://dl.acm.org/doi/10.1145/3320269.3384721)"** *(ACM ASIACCS 2020)*

Dictionaries that W2E uses can be found in [GitHub](https://github.com/Samsung/W2E).

### [Detected events]({{ site.baseurl }})
Detected events are posted as table. Results will be updated daily basis.  
Each row represents an event.  
Meanings of columns are
- Category  
Category of the event. One of [exploit, vulnerability, malware, privacy, breach]
- Keyword  
Keyword of the event. This includes new words or re-emerging words.
- Representative tweet  
Representative tweet of the event.
- Mentioned  
Count of tweets that mentioning the event.
