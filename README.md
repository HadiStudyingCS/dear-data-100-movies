# dear-data-100-movies
This is my Dear Data 100 assignment part of my creative coding course in university, studying computer science year 1
# Dear Data 100: Movies

# What this is
This is my Dear Data 100 project for IN1007 Java Programming (#CreativeCoding). It's a Processing sketch that shows 100 movies I've watched. Instead of just listing the movies, it shows how each one affected me, if where i watched it has any affect, and what memories are attached to it.

The idea comes from Dear Data by Giorgia Lupi and Stefanie Posavec, where everyday life is turned into data and drawn as visuals.

# Why movies?
My whole life movies have been an escape for me, ive always allowed myself to be immersed into a fictional reality, a fantasy where i feel and connect with the characters and events. Since i aim to watch a movie a day (sometimes 2) I wanted to see if any patterns show up when I look at all of them together, for example whether certain emotions go with certain places or memories.

# The data
All the data is in movies.csv. Each row is one movie, and each movie has seven pieces of information:

- title: the name of the movie
- year: the year it was released
- rating: my score out of 10
- mainEmotion: the main feeling it gave me (laughed, cried, scared, inspired, nostalgic, bored)
- memory: the memory or time in my life it's linked to (childhood, family, friends, school, travel, none)
- location: where I watched it (cinema, home, friends-house, phone-or-laptop, other)
- recommendTo: who I'd recommend it to (everyone, friends, family, nobody)

I used fixed lists for the emotions, memories, locations and recommendations so the data stays consistent across all 100 movies. I started by writing down movies that have affected my day-to-day life and have stayed lingering on my mind for many years, and throughout the list i would put in the movies i watched that day or recently.

# How the sketch will work
Each movie will be an object made from a Movie class. The sketch reads movies.csv, creates one Movie object per row, and draws each one. The details of each movie (like emotion or rating) will control how it looks, for example its colour, size or shape. I'll update this section once the sketch is built.

# How to run it
1. Install Processing from https://processing.org/download
2. Download this repository
3. Open the sketch file in Processing and press Run

# Notes
No names of other people are in the data. People are only recorded as groups,
like "friends" or "family".
