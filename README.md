# Trading Strategy From Signals

We are taking a csv, with two columns signal and equity. 
Constructing a trading strategy that beats a baseline strategy that selects every signal

## Overview
There are 5 jupyter notebook
1. My Methodology and Thoughts
   - This is exactly what it sounds like, I feel like its easier to follow and trace my thought process in one (kinda) long document basically walks through my decision making, the choices i've made and why.
   - It doesn't really go into much detail on the statistics because then there wouldn't be a point of looking at the other notebooks but does highlight some stand out statistics.
   - It may be a little redudant when you're in the notebooks because it could say something similar or near similar (sorry)
2. Data Preprocessing
3. Understanding the signal column
     - This is crucial in how we determine our trading strategy
4. Implementing our trading strategy and looking at the comparison to our baseline strategy
5. Optimization
   - I kind of nerded out on this, it wasn't necessarilly asked for but I like this stuff
   - Due to time constraints i wasn't able to incorporate this into the trading strategy but was able to get some interesting results.

## Getting this going
  - There are some instructions, in the data preprocessing to set up some folders that are in the gitignore
  - You will need the dataset to put in a ../data/raw/ folder to get it to read
  - You will also need to create a ../data/processed/ folder that should receive processed csvs.
