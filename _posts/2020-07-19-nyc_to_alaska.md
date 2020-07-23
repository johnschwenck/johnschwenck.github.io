---
layout: post
title: NYC to Alaska
subtitle: Reflecting on a 5,775-mile data-driven bicycle trek across North America
cover-img: /assets/img/20190703_171742.jpg
date: 2020-07-19 
tags: [cycling, research]
---

Exactly one year ago today, on July 19th 2019, I completed what seemed like an insurmountable goal of riding my bicycle 5,775 miles across the North American continent from Central Park, New York City to Seward, Alaska. [Here's proof.](https://app.powerbi.com/view?r=eyJrIjoiYjdmYTAzMmEtZjllZS00Mzg4LTljZDMtMTQ1Y2EyODJkNmQ1IiwidCI6IjY4ZjM4MWUzLTQ2ZGEtNDdiOS1iYTU3LTZmMzIyYjhmMGRhMSIsImMiOjN9)

<img style="float:left;padding-top:20px; padding-bottom:20px; padding-right:20px" width="420" height="270" src="/assets/img/R4R_post/MT Missoula 2.jpg"/>
It took 95 days and spanned 13 U.S. states and 3 Canadian provinces. I endured sandstorms, tornadoes, subzero temperatures, thunderstorms, blizzards, mudslides, hailstorms, forest fires, and came within an arm's reach of over 14 different species of voracious wildlife including grizzly bears, moose, bison, and mountain lions all while riding my father's beat-up 28-year-old 1991 Cannondale bicycle.

It was the ultimate test of mental endurance. While I knew it was not going to be some ebullient happy-go-lucky joyride, I never expected to face such an incessant barrage of bad luck. What I encountered was nothing remotely close to what I initially had in mind. Between the never-ending gravel roads and the inclement weather that seemed to follow me no matter what part of the country I rode in, I couldn't seem to catch a break.

<img style="float:right;padding:20px" width="400" height="400" src="/assets/img/R4R_post/day1.jpg"/>
Speaking of bad weather...

Quite comically, within the very first 10 minutes into the trip it started to downpour so hard in NYC that I could barely see in front of me. I ended up doing a full 7-mile loop detour around Central Park. I didn't even realize I did so until I saw at least 50 text messages asking me what on earth I was doing and proceeded to check my Strava recording later that night. Ironically, with that added detour, I only managed to make it back to my hometown - I was off to a great start.

I assume at this point you naturally are asking yourself one of two questions: why I am posting this on a professional networking site and/or why on earth I would ever want to ride my bicycle that far. I'll begin with the latter.

To be completely honest, I wasn't a diehard cyclist prior to that trip. When I think about it, I wasn't even *any* kind of cyclist. I first hopped on a bike and started training for the trip a couple months before I left, and by "training" I mean riding 10-15 miles a few times per week. To put this into perspective, during my trip I averaged around 70-100 miles per day. My initial goal was 50 miles per day until I hit Indiana and saw my first tornado, at which point I convinced myself to start pedaling 100+ miles per day just to get the Hell out of the Midwest.

I would always have a few humorous anecdotes in my back pocket for reasons to tell people I met along the way as to why I decided on such an undertaking; I always tried to keep it short because I knew I would be saying these narratives over and over again. I usually gave people the joking answer that I wanted to "one-up" my father who also rode his bicycle across the U.S. when he was 25 in 1991, who "only" went 3,200 miles from NJ to San Diego (which, I think it's safe to say I have him beat!). Alternatively, I would use the reason of finishing both my parents' bike trip to Alaska that was cut short because of... me being born. The real reason is that I wanted to achieve something unique that most people have never done in their entire lives. I have an insatiable competitiveness within me that simply needed an outlet to push myself to the absolute mental and physical limit.

However, there was another, perhaps more surprising, reason. As an aspiring statistician, naturally I wanted to conduct research and collect data on myself. If I was going to embark on such an endeavor, I wanted to make sure that I could use it to my advantage. I wasn't content with basic summary statistics of what my average heart rate and total distance were. I insisted on collecting extremely granular data that encapsulated all parts of my medical well-being; health data such as second-by-second heart rate, heart rate variability (HRV), sleep stage duration, blood pressure, nutritional diet information and food logs, activity data, electroencephalography (EEG) data, electrocardiography (ECG) data, and not to mention the dozens of geospatial variables such as elevation, distance, wind speeds, weather, etc.

<img style="padding-top:20px; padding-bottom:20px" src="/assets/img/R4R_post/20190626_114807.jpg"/>

Growing up, I was always taught that to become a leader, you must learn to lead with your boots on the ground (a military adage from my parents owing to the fact that commanders who fight alongside their subordinates "on the ground" in the actual combat will have their full support, opposed to those in charge who relegate their responsibilities to others). In a research context, if there is an unexplored hypothesis or an underdeveloped area of science, don't wait around for others. Roll up your sleeves, form a plan, and run the experiment yourself.

That unexplored area for me lie in a minor detail of having a fairly unique heart condition (an enlarged aortic root and a bicuspid aortic valve) whose typical profile didn't seem to match my highly active persona. Because of this inconsistency, there wasn't much available research for doctors to safely deduce conclusions from. To err on the side of caution, they suggested I shift away from anaerobic exercise to aerobic exercise. My entire life, I played sports that required vigorous weight lifting exercise (football, rugby, lacrosse), so this was a pretty big adjustment. I was never a big fan of running or swimming, but I was always inspired by my parents' tenacity and passion for cycling. It didn't take long before I saw this as a golden opportunity.

Not only would this become one of, if not, *the* largest data collection efforts for endurance cross-country cycling, but to the best of my knowledge there were no previous multivariate time series physiology studies specifically aimed at sustained aerobic exercise for endurance cycling in general, let alone for a nearly six thousand mile duration.

While perhaps naive at the time and having not yet acquired my theoretical statistics foundations, my mentality was to collect as much data as I can and interpret it all later during my graduate studies. It somehow never occurred to me to consider the most basic ramifications of collecting non-iid data for a single sample. However, I knew that despite this idea being merely nothing more than a super involved uncontrolled n-of-1 pilot study, I was determined to at least try and make sense of it all. The conclusions I would draw would not be representative of the population, but would at the very least allow me to build personalized algorithms for my own well-being (keep an eye out for a subsequent post on this). Not to mention it would also serve as a baseline and something to improve upon in the future with more participants.

<img style="float:right; padding:20px" src="/assets/img/R4R_post/twoface.jpg"/>
With heart disease being the leading cause of death worldwide, I figured some doctor somewhere in the world could better assist their patients if they could utilize my data to aid in their decision making. If the results of my trip could help just one person in some way, then to me it is a worthwhile endeavor. I therefore felt obligated to contribute my data publicly and host everything through the Harvard Dataverse (found [here](https://dataverse.harvard.edu/dataverse/r4r)).

And just like that, I was off. 95 days and 5,775 miles of lugging 100 pounds of gear, perpetually waterlogged clothes from the rain, and a handful of gadgets tracking my every move and frustration from every obstacle I faced. I even had a (now defunct) website that allowed you to track every single data point and map my progress each day. As the image on the right shows (day 1 vs day 95), you could also track the progression of my face!

There were moments of doubt, exasperation, and suffering, but there are not enough words to describe the feeling of crossing the finish line knowing that what you just achieved is more than you (or anyone else for that matter) could have ever imagined.

<img style="padding-top:20px; padding-bottom:20px" src="/assets/img/R4R_post/mountain.jpg"/>

So here we are, one year later.

I haven't changed the world yet (although I did cross 1/4 of it) and I'm nowhere near the pinnacle of my career. I did, however, learn a few lessons along the way that have helped me in situations I never thought possible.

For starters, the data from this adventure forced me to learn how to efficiently code in a multitude of programming languages (R, Python, C++) and visualize data effectively (Power BI). I learned how to scrape data from the web, how to utilize APIs through tools like Postman, and how to build classes and objects for various data sources. As I explore and think about various statistical applications in other domains in my graduate studies, the more I find myself coming back to the bike trip data with new and refined ideas. At the time of writing this article, I am currently in the midst of developing an application that will allow others to collect data from essentially the same variables so that my seemingly trivial n-of-1 study matures into a representative and hopefully useful tool for those looking to track their medical well-being in the future.

The day after I finished my trip, a family member asked me what the biggest takeaway was. For reasons that are beyond me, I was completely dumbfounded as if I somehow wasn't expecting such an obvious question. Needless to say, I didn't have an answer. Admittedly, I was pretty fed up with the terrible weather and was definitely not in the best of spirits at the time. However, since that day I've been able to reflect on my ride and approach problems with a different perspective.

My goals today are a stark contrast to what I had in mind one year ago, but in my opinion if you are the same person now as you were then, you haven't grown at all. I recently came across my [interview with KPAX Montana](https://www.youtube.com/watch?v=r59opEGhA6I&feature=youtu.be) from my trip and was amused by how my research plans have twisted and turned since then. As with most promising ideas there is a natural "hype cycle" that follows, but getting that initial idyllic phase out of the way allowed me to look at previous concepts with more clarity and empiricism and allowed me to better understand the mathematical principles that assess their legitimacy. No matter how seemingly insignificant you may think your ideas are, stay curious and never stop questioning the world around you. Those theories can always be refined down the road.

I realize very few people will ever be able to comprehend what I've had to go through during my trip to achieve such a feat, but I also realize that the lessons and takeaways I've gained are ubiquitous and apply to everyday situations. In the spirit of LinkedIn professionalism, I've come up with a list of 5 lessons learned directly from my trip that have helped me in my career and in other areas of life. My hope is that you don't find these as mere banalities, but that you can somehow relate to them in the future.

<img style="padding-top:20px; padding-bottom:20px" src="/assets/img/R4R_post/CA rockies.jpg"/>

##### Takeaway #1: Don't look back

I will never forget the morning just before arriving in Central Park when I started thinking to myself, "what if I don't make it?" and immediately felt anxious and nervous about what would ensue. I was leaving a great job that was stable and paid well to pursue the unknown. It didn't help that once the word got out that day about my trip that seemingly every news reporter in the area was ringing my phone off the hook asking a million questions I did not have the answers to.

We've all experienced this kind of anxiety at some point in our lives and we know that once we get those initial butterflies out of the way, the rest is easy. However, there are some instances where we hesitate to act and often decline to pursue that goal. Sometimes there are perfectly legitimate reasons, but oftentimes it is due to fear or because we feel that the task is too daunting. Sometimes you'll find yourself in a situation where at one point you could have altered the decision that was made, but now feel that you may have made the wrong decision (also known as hindsight bias). Do not be afraid of failure. If you make a well-thought out decision, commit to it and don't look back. Form a plan, think through whatever can still be controlled and forget the rest. Nobody can judge you for trying; if it doesn't pan out how you expect, you will most likely learn something in the process.

I truly believe that taking a leap of faith into the unknown will inevitably make you a stronger individual in all aspects of life. Failing sucks. I will be the first person to admit it. But never trying in the first place is unfathomably worse.

*"Life is either a daring adventure or nothing" - Helen Keller*

<img style="padding-top:20px; padding-bottom:20px" src="/assets/img/R4R_post/20190702_230912.jpg"/>

##### Takeaway #2: Don't be a selfish bastard and treat everyone with respect

I couch-surfed the majority of the way across "the lower 48" (U.S. states). The single most defining moment of my trip was in the middle of Illinois. The guy I was going to stay with for the night texted me letting me know that he had been preparing a nice dinner for me for when I got there and that he was excited to talk and hear about my trip thus far. He lived in a poverty-stricken trailer park home where abandoned cars were decaying in the lawn with missing tires, rabid dogs abound, and every other trailer was dilapidated. To my surprise, and despite the ominous atmosphere, he ended up being one of the most selfless kindhearted people I've ever met in my entire life. The dinner he made wasn't anything special; it was a microwave dinner with a side of wings and a soda. He literally had nothing, but he was a hard-working guy who, no matter how many lemons life threw at him, was always willing to care for other people and made it his priority to make them feel welcome and comfortable. There is a lot to be learned in a professional setting from people like him.

Not judging others and being selfless is such a simple concept, but for some reason it never seems to get through to people. At my former company, I was fortunate to have experienced first-hand arguably the best manger you could have, but a close colleague of mine unfortunately had the polar opposite. It was straight out of a business textbook. My manager grew himself by growing his team first and always knew when to teach and when to let us struggle through to find the answers ourselves. He took the fall for our team's failures and spread the credit when we succeeded. My colleague's manager on the other hand was a nightmare and was a completely insecure, self-seeking person who took the credit for projects he never even touched. My former manager has graduated to Vice President; the other manager has remained at supervisor. They both started at the same entry-level position at the same time 8 years ago. Don't be selfish.

*"Great minds discuss ideas; average minds discuss events; small minds discuss people" - Eleanor Roosevelt*


##### Takeaway #3: Control what you can, forget what you cannot, and be dynamic

Bar none, the lowest point of my trip was being stuck in Casper, WY for 4 days because there was literally too much snow for me to continue riding - even if I wanted to.
<img style="float:right; padding-top:20px; padding-bottom:20px; padding-left:20px" src="/assets/img/R4R_post/20190625_104425.jpg"/>
By sheer luck, on the day before all the snow, I met a guy on his motorcycle who had been returning from his own mini-adventure. He was so perplexed by my trip that he offered his home in Casper in the event I needed somewhere to stay. The distance from the rest stop where I met him to his house was a solid 80 or so miles away and I had already rode 40 miles that day. I didn't think I would make it that far, but once the lightning started chasing me I realized I didn't have any other option. Once I made it there, I was then stuck as it proceeded to snow day-in, day-out for the next 4 days. (On a side note, I am beyond grateful to have met such a genuine person and wonderful family who spared me the hassle of setting up a tent in the snow for that period of time.)

I had a terrible disposition up to that point because there were only a handful of days with good weather since I began and every other day was terrible. Before long, it started to really get to my head and because I was so fed up with all of it, I started to contemplate alternative courses of action. My most convincing alternative was to change my target from Alaska to Seattle so that I could at least go coast to coast.

However, I simply couldn't bring myself to not finish what I had set out to do and I knew I would regret it for the rest of my life if I quit. I realized that the weather is simply beyond my control and that it wasn't worth my energy since there was nothing I could do about it. The only thing I could control was to prepare for it, take it a day at a time, and think about where I would end up for the night.

I firmly believe that you have to be dynamic and willing to adapt to any situation that is thrown your way. When it snowed, I took refuge indoors. When temperatures dropped below freezing, I pedaled as fast as I could to keep warm. When my clothes were completely soaked, I'd build a fire to dry them out. When I crashed or fell, I would find an old shirt to wrap up the wound in order to keep moving forward. You will not win every time, but the goal should be to win more often than not. Win the war, not the battle.

This is an important philosophy that I have carried with me to this day. Believe it or not, I’ve experienced more self-doubt and inhibition during my last semester as a graduate student than I experienced the entire bike trip. My first semester proved to be an especially humbling experience. I received grades lower than I expected on exams, but I knew there was no sense in dwelling over what could have been. The only action I could take is to try and score higher on the next one. There is only so much I can study, and once the exam is submitted there is nothing more I can do about it. Talking about the test with classmates, or trying to work through exam problems to see if and where I went wrong would prove deleterious. I simply had to shift my attention to other classes and wait until the exams were graded to figure out what went wrong. The following semester, I re-prioritized my schedule, maintained better time management and finished remarkably better. Discerning between what I could control and what I couldn't allowed me to focus my efforts more intently. I let go and forgot about everything that was out of my control for the time being.

The ups and downs of life are inevitable, it is up to you to choose how to handle them.

*"Do what you can, with what you have, where you are" - Theodore Roosevelt*


##### Takeaway #4: Focus on Today.

One of the most pivotal decisions I had to make during the trip was when I reached Jake's Corner in the Yukon Territory (Canada); I had to decide whether to peel off down towards Skagway (right near Juneau in the southern panhandle of Alaska) and finish the trip within a day or two, or to continue riding into mainland Alaska.

At that point, the psychological toll of having been perpetually rained on with horrible bouts of weather almost every single day began to wear me out. Not to mention, I could literally see Alaska off in the distance. The temptation was analogous to dangling a doughnut in front of someone trying to lose weight.

![Jakes Corner, Yukon Territory, Canada](/assets/img/R4R_post/newjakescorner.png)

I kept going. I knew that if I finished in Skagway, I would never forgive myself for not going all the way. I've been dreaming of going to Alaska since I was young and I wasn't about to trip in front of the finish line and not explore all that it has to offer. From Jake's corner, I rode nearly 700 miles up to Fairbanks. Once I made it to Fairbanks, I figured I also wasn't really in Alaska unless I got to see Mt Denali, the highest point in North America, so I rode another 250 miles down to Talkeetna. Then, for logistical reasons, I had to make it down to the coast to catch a boat back down to the lower 48 so that I could return home. Tack on another 250 miles down to Seward. By the time I was finished, I had rode an additional 1,200 miles more than if I simply ended my trip in Skagway.

The key for me lie in not focusing too far into the future, but rather on incremental progress each day. If I focused on how far I still had to ride, I would get flustered and start to second guess myself. I already knew what my long-term goal was, I just had to execute in the short and intermediate term to get there.

When I was working for my former employer prior to my trip, I would maintain the same mentality. There was one particular project that was a major transformation for the entire business that I was assigned to which required working with every department to build a company-wide dashboard. If I started to think about the magnitude of the project scope, I would get nervous. Instead, I focused on the intermediate goals of listing each department that I had to work with and set up short term goals to achieve them such as setting up meetings, automating certain workflows, etc. In this case, my prior work experience luckily came in handy for my bike trip, instead of the other way around.

We often get lost thinking about how the repercussions of our actions today will affect tomorrow instead of simply focusing our energy on how to actually complete today’s mission.

*"Many of life's failures are people who did not realize how close they were to success when they gave up." - Thomas Edison*



##### Takeaway #5: Be comfortable being uncomfortable

I tend to think of the entire trip as two separate excursions: the lower 48 and Canada/Alaska. For the first half throughout the lower 48, I relied on couch-surfing, battling abominable road conditions that tried to slow me down in every way possible, and subtly camping in places that I probably shouldn't have been. It was a blitzkrieg. The second phase, on the other hand, was completely different. It was a war of attrition. Weather wasn't my main problem anymore: it was survival. There were week-long 500-mile stretches without any kind of grocery store or gas station, or cell-phone service for that matter. It was terrifying, yet exhilarating.

The second phase is where I first encountered any kind of vicious animal. I remember vividly my first encounter with a bear. I had enough people telling me stories of vicious bear attacks to feel pretty uneasy when I crossed into the so-called bear country. No more than 10 miles into the Canadian National Parks I see a decent sized black bear on the side of the road. If there was a moment of terror, this was it. I started yelling at it and waving my arms up and down like a maniac to try and scare it off (this is actually what you're supposed to do according to the National Park Service) but it wasn't going anywhere. It just kept on eating its berries. While I was a frantic mess, there was a cyclist coming from the other direction who shouted "hey bear!" and rode right past it without batting an eye. When I saw that, I had no other option. I had to move. What must've looked extremely awkward for anyone watching me, I mustered up the courage to start pedaling and continued on. Just when I thought it was over, there was a cub another mile down the road with its protective mother not too far away. I just gripped my bear spray and hoped for the best. Another success. This happened over and over again for the rest of the trip. By the end, I probably came in contact with over 100 bears. Eventually, you become comfortable in those uncomfortable situations and learn to adapt and react strategically.

It is important to note that comfort in being uncomfortable does not imply complacency by any stretch. It implies quite the opposite. Complacency, by contrast, will get you killed.

Therein lies the difference between a vacation and an adventure. An adventure is not easy or relaxing. If you worry more about how you could die rather than ways to explore new things, you aren't living and you are depriving yourself of a fulfilled existence. No matter what obstacles stands in my way going forward, it pales in comparison to what I experienced on my trip last year. Nothing will be as bad as nearly dying of hypothermia because of riding in the snow with completely drenched clothes from the previous day's thunderstorm. Nothing will be as bad as riding with a broken collar bone after a bad crash. Nothing will be as bad as biking through a sandstorm and hailstorm simultaneously and having the hail burn my skin. This trip was never about "becoming in tune with nature" or finding myself or for any other hippie-dippie reason. I really just wanted to see how hard and how far I could push myself, and I ended up shattering my own expectations. It was not the adventure of a lifetime, but rather one of hopefully many more adventures yet to come.

*"If you're going through Hell, keep going" - Winston Churchill*



If you want more of the details of the actual trip, there's no better way to view it than through the data. I'll throw in another shameless plug for my dashboard once again here, but as a thank you for making it to the end of my first LinkedIn post, I'll also leave you with a few fun statistics (prone to device measurement error):

- Farthest distance: 182.2 miles (July 3rd/4th, 2019)
- Average distance: 71.49 miles per day
- Fastest speed: 41.26 mph (April 16th, 2019)
- Highest altitude: 6,860 feet (June 10th, 2019)
- Steepest gradient (Incline): +30.89 degrees (April 17th, 2019)
- Steepest gradient (Decline): -33.41 degrees (April 25th, 2019)
- Strongest headwind: 31.09 mph (May 1st, 2019)
- Number of days rained: 51 of 95 days (52.64%)
- Wildlife encountered: grizzly bear, black bear, moose, bison, horse, porcupine, wild dogs, antelope, mountain goat, bald eagle, sea otter, whale, marmot, big horn sheep, cow, snake

Considering the book Into the Wild by Jon Krakauer was a huge inspiration for my Alaskan final destination, it is only fitting that I end this post with a quote from Christopher "Alexander Supertramp" McCandless:

*So many people live within unhappy circumstances and yet will not take the initiative to change their situation because they are conditioned to a life of security, conformity, and conservatism, all of which may appear to give one peace of mind, but in reality nothing is more damaging to the adventurous spirit within a man than a secure future. The very core of a man's living spirit is his passion for adventure. The joy of life comes from our encounters with new experiences and hence there is no greater joy than to have an endlessly changing horizon, for each day to have a new and different sun.*

When in doubt, look north to the future. Ride on!
