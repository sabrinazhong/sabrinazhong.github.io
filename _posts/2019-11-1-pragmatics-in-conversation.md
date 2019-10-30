---
layout: post
title: "Hey, it is hot here..."
date: 2019-11-01
---

June 11, 2019, the weather in San Francisco soared to 97 degrees Fahrenheit. It was hot. I was chilling on the couch
(not really, not chill at all) after I got home from work. It was hot and stuffy in the living room. I wondered whether
the voice assistant connected to the thermostat at home could help me to cooler the space.

<i>"Hey, it is hot here."</i>

I was expecting that they could understand it and adjust the temperature for me. However, my voice assistant told me,

"It’s not hot right now in San Francisco. It’s 81 degrees."

My immediate thought was, “that’s sassy... 81 degrees Fahrenheit indoor at 9 pm is very hot to me." Then, I, as a linguist,
subconsciously started to think, “what went wrong here?”

I personally think there might be two types of explanation--one is related to ASR (auto speech recognition) and the other
one is related to NLU (natural language understanding). Either way, the computer could not correctly understand what I mean
by “here.” I was definitely not talking about the weather in San Francisco. Instead, I was referring to the room temperature
in my house. The thermostat showed it was 90 degrees Fahrenheit :(

ASR is to transcribe someone's speech for computer. It could be possible that the computer recognized my speech as a question
rather than a statement--“is it hot here?” or “it is hot here?” with an rising intonation.

Or, the the computer did get the correct input that I said it was hot. However, it failed to understand the pragmatics in the
sentence, which is related to NLU. The Gricean Maxims, purposed by a philosopher, Paul Grice, are four ways to explain how
interlocutors in a conversation stay cooperative and achieve effective communication. However, in reality, people don’t
usually mean what they say, people don’t usually say what they mean. In the above dialogue , “it is
hot here” flouts the maxim of relation and the maxim of manner. I didn't directly address my intention, and it is unclear
what I wanted to do.

Therefore, it is sort of suprising but not really that my voice assistant could not help me. Several issues might be involved
here, and people in academia and the industry are still trying to solve issues like those. It is already very impressive
how powerful and useful voice user interfaces are nowadays. Thanks to numerous software engineers, linguists, designer, and
many other people!

However, in the short future, I hope my voice assistant can understand what I really mean. Maybe, one day, my voice assistant
and I can have a conversation like this:

"Hey, it is hot here."
"Totally, is there anything I can do for you?"
"Turn on the AC." or "Set the room temperature at 75."

First, I hope that my voice assistant can agree with me rather than telling me they does not think so. To be fair,
81 degrees Fahrenheit is definitely not cool.

However, if it is “smart” enough, the voice assistant may be able to propose a solution in return.

"Hey, it is hot here."
"Ya, it seems the windows are closed. Do you want me to open the window for you?"

The home automation system detects that all the window in my house are closed. It might (or might not) be windy or cooler
outside, but opening the windows seems like a reasonable solution.

Or, the home automation system detects that I usually turn on the AC when the room temperature is at that level. Then,
they figures out that I am probably asking them to turn it on for me.

"Hey, it is hot here."
"Ya, it seems the AC is off. Do you want me to turn it on?"

Well, you may say "why not just tell your voice assistant to open the windows or set the room temperature? Isn't that
easier?" Of course, that definitely is going to work. However, as I mentioned above, people don't usually say what they
mean. You certainly don't want the voice assistant to call 911, when someone says, "I'm dying" or "I'm starving" unless there is a real emergency. Or in the future, we don't just treat voice user interfaces as robots or computers only--they will more be like our personal assistants. Moreover, if human always just give direct commands to their voice user interfaces, what's all the fun about playing with language?
