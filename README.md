# Hindu-Calender

### Function
This project calculates various calender values that are relevant in Hinduism. Below is a list of some of the functions crated and a description of what they calculate.

- getTithi(date)- calculates [Tithi](https://en.wikipedia.org/wiki/Tithi)
- getNakshatram(date) - calculates [Nakshatram](https://en.wikipedia.org/wiki/Nakshatra)
- getRahukaalam(date, latitude, longitude) - calculates the start and end time of [Rahukaalam](https://en.wikipedia.org/wiki/Rahukaalam)
- getPaksham(date) - calculates [Paksham](https://en.wikipedia.org/wiki/Paksha)
- getVasaram(date) - calculates day of the week 

### To-Do
Apart from these basic calender events it would be interesting to also track the solar month system, lunar month system, [Ritu (season)](https://en.wikipedia.org/wiki/Ritu_(Indian_season)), Yoga, and Karana.

The diversity of languages and variances in how these calender values are indexed from region to region make it difficult to call the calculations "correct". Some people may find that these values are off by a few hours because of the definitons of different calender values assumed in this project. I hope to make a UI for this tool that allows the user to customize this tool based on their language and indexing method. 

## Citation
I used some code from [here](https://github.com/mourner/suncalc) for some basic astronomical values.
