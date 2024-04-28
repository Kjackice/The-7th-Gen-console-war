# The 7th Gen console war

In this project, I aimed to find and inspect data from the 7th generation of consoles. I primarily sought answers to questions I had when these were considered current technology. This post will lay out my thought process during information gathering, data cleaning, and my final analysis.

## Sources

All information and data was scraped from [VGChartz](https://www.vgchartz.com/), [Wikipedia](https://en.wikipedia.org/wiki/List_of_best-selling_game_consoles_by_region), and Units sold Per Million. *Numbers have also been rounded to the nearest 10th.*

## A Brief bit of context

The 7th Generation “Console War“ is what video game consumers titled the sales competition between tech companies Sony, Microsoft, and Nintendo. Beginning with the release of Microsoft’s “Xbox One” in 2013, followed by Sony’s “PlayStation 5”, and finally Nintendo’s handheld/console hybrid “Nintendo Switch”.

## The Process

I started my process by writing down some basic questions, like “How many units were sold?” then I expanded into more detailed questions to drive my analysis. Before I could answer those questions I had to clean and narrow down my data.

I required data only from the last decade, thus information prior to 2010 was irrelevant to my analysis. My initial step involved data cleaning where I converted the release dates to just the year, used the "TRIM" function to eliminate extra spaces, and ensured text strings were consistent. I noticed blank fields in some video game entries, so I used formatting conditions to highlight all the fields with missing information in bright red. After identifying these fields and converting all dates to display only the release year with the "YEAR" function, I conducted an additional sweep to identify any potentially incorrect data or errors.

With the first pass-through finished, I can start sorting and filtering information to narrow everything down to video game releases from the year 2013 to 2023. This is the time range for my analysis and the release year/succession year for the 7th generation of gaming consoles. With everything narrowed down and sorted by year, I then begin the second pass-through for cleaning. This time I’m looking for text errors like typos and weird spacing. Another issue I ran into was that some video games titles contain a year, games like “Cyberpunk 2077” or “The Order 1886” needed to be double checked just incase they get parsed as “time/date” data.

After finishing up the foundational cleaning steps I use conditional formatting to make all releases under “PlayStation”, “Xbox one”, and “Nintendo switch” Blue, Green, and Red in that order.

# Charts and More Charts

Now that the cleaning process is finished, I can move on to answering some questions. Below features charts on Console market performance and Units sold:

https://public.tableau.com/shared/JWCJJDF6F?:display_count=n&:origin=viz_share_link

## Game Sales Over Time:

https://public.tableau.com/views/Consoleperformancebygamesales/Sheet1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

# Questions and Answers

Looking at the data allowed me to find answers to questions I didn’t initially have. The main goal of this analysis was to find out which Console finished the 7th generation sales race the strongest. Something to keep in mind is that the Nintendo “Switch” was released a couple years after the “Xbox One” and “PlayStation 4”, I’ve taken into account how an asynchronized release schedule might impact the overall outcome. To avoid as much bias as possible, I offset the release year of the “Switch” so the data is fairly being compared. 

Total sales throughout the years are split between Hardware sales and Game sales (Also known as software sales). Visualizing the data this way allows me to have an overview of information for my analysis. The first chart shows a clear different in total Hardware sales vs Game sales. PlayStation earning significantly more in Game sales despite being behind in Hardware sales is interesting but understandable, I found during this time Sony and Microsoft prioritized Software over hardware sales and have maintained this stance today, finding more success in pushing video games over selling platforms. The impressive sales from PlayStation can be attributed to the combined numbers from top performing titles like “Marvel’s Spider-Man”, “Grand Theft Auto V”, and “Last of Us Remastered”. Along with multi-platform releases such as “Fallout 4”.

Nintendo on the other hand specialized in first party releases, the top charting game sales are all developed in-house by Nintendo. The number one highest performing Nintendo title being “Mario Kart 8 Deluxe”. Nintendo’s top-selling game compared to other systems top sellers is fairly unique. Its primarily a Multi-player game, focused on larger play groups rather then a story driven, solo game like “Grand Theft Auto 5”. Being able to play video games with friends and family is a pretty effective selling point for a game and it generates natural advertisement via word-of-mouth. The game was also bundled with the initial release of the system, almost like a free sample for early investors. Additionally Nintendo found more success with this strategy compared to Sony and Microsoft, who also had games bundled with the launch of their consoles.

It's important to note that these consoles are priced differently. The "Switch" is priced at 299.99 USD, "PlayStation 4" at 399.99 USD, and "Xbox One" at 499.99 USD. This pricing affects the consoles' accessibility in the market. A lower entry fee leads to more owners and a larger user base, which *can* result in increased game sales. The "Nintendo Switch" leads in hardware sales, and the stated factors explain why that is. In second place, the "PlayStation 4" has slightly lower hardware sales but leads in game sales. It became a popular choice for multi-platform releases and has its own exclusive games, giving users more reasons to choose Sony's console. Games like "Marvel’s Spider-Man" significantly contribute to the PlayStation 4’s strong game sales. Unfortunately these same factors did not help Microsoft’s “Xbox One”.

Microsoft's "Xbox One" was priced higher at launch compared to its competitors, offered a limited exclusive catalog, and overall lacked the characteristics that made Sony and Nintendo's systems appealing to potential customers. Microsoft’s overall best selling exclusive was “Halo 5 Guardians” and featured a handful of launch titles like “Dead Rising 3”. Looking into the performance over the years has lead me to the conclusion Microsoft did not reach expected sales numbers, it lagged behind its competition in hardware and game sales. Even for multi-platform releases like “Grand theft Auto 5” consumers seemed to prefer the “PlayStation 4” over “Xbox One”. 

# Conclusions

The final conclusions I reached were driven by data. In addition to this data, I conducted further research into the gaming "landscape" at the time. Combining the data with context provided a much more thorough final analysis. Early in my analysis I expected Nintendo's “Switch“ to hold the majority of the achievements, but after my process I was pleasantly surprised to see that Nintendo didn't steal every achievement.

### Top selling Game

“Mario Kart 8 Deluxe”

### Top selling Hardware

“Nintendo Switch”

### Overall most sales combined

“PlayStation 4”

### Most game sales

“PlayStation 4”

### Most Exclusive Sales

“Nintendo Switch“

### Overall Best Year

2017
