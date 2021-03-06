## What's the story?
All too commonly, we're presented huge amounts of data in the form of tables and have to make sense of that mess.

Can we use visualizations to present the information more effectively, and ideally tell a story about what the data mean and why they're important?

In this exercise, we will be looking at some aggregate statistics from a recent [Demographic and Health Survey in Rwanda](http://dhsprogram.com/pubs/pdf/PR65/PR65.pdf).  Your task, should you choose to accept it, is to take this table on child malnutrition in 2014-2015 and figure out a story to tell.

### The Data
Here's how the data look directly in the report:

![DHS Rwanda Stunting](/Day4/Data/RwandaDHS_2014-2015-34.png)


... as you can see, there's a LOT going on, and the data, while organized rationally, don't tell that much of a story and aren't in the best form for direct analysis and visualization. We're nice, though, so we have the raw data for you [here](https://github.com/GeoCenter/StataTraining/raw/master/Day4/Data/dhs_data_rwanda.xls).

There's also lots of different angles you can take on the data: do you look at stunting (height-for age < -2 SD from mean)?  underweight? (weight-for-height < -2 SD from mean)? wasting (weight-for-age < -2 SD from mean)?  All three?  And what are you going to compare?

Data are taken from the 2014-2015 Rwanda Demographic and Health Survey [Key Indicators Report](http://dhsprogram.com/pubs/pdf/PR65/PR65.pdf)

### Step 1: Sketch
Pen and paper is often the best first tool to figure out what you want to do and say.  Don't be afraid that you're not a good artist-- I'm certainly not. All you need to be able to do is to make your drawings meaningful to someone else, and that honestly doesn't take much.

Examine the data in the table.  Determine:
* What patterns exist in the data?
* What relationship(s) do you want to show?
* What part(s) of the data do you want to use?
* Who is your audience?
* How do you want the audience to use the data?

Then, using that info, sketch at least one way to represent part of the data in a new way.


### Step 2: Convert the sketch to a polished graphic.
Feel free to use *any* tool that you want to reimagine the data.  Here's a few suggestions:
* **Stata** - Try using the Graphics menu bar to make a plot, or get bold and write things from the command line. The Plotting in Stata cheatsheet should help.
* **Excel** or **Google Sheets** - Excel can make nice, meaningful graphics.  Just be careful about changing the default options; they're rarely the best approach (though Google Sheets is much better).
* **Tableau** - if you have access or want to try out [Tableau Public](https://public.tableau.com/s/), go for it!
* There are many more options, from low-tech (Paint?) to high tech (D3). Go nuts!

### Step 3: Refine
Good ideas aren't necessarily the first thing you try; iteration and outside opinions are critical.  When you get feedback from yourself and other, ask:
* Does the plot show the relationship I want?
    * Are the data (and most importantly, the key comparison / relationship you want to highlight) the focus of the visualization?
* Will it be useful to the audience?
* Is the plot type successful? 
    * Would another type be better?
    * Would the data be better viewed as small multiples, rather than having overlapping plots?
* * Can you understand the plot with little verbal explanation?
    * Can annotations help draw comparisons or highlight interesting parts of the data?
* Is every dot, symbol, color, line, and variable necessary?
    * Keep things simple, consistent, and meaningful
* How should the data be grouped / arranged / combined?
    * Alphabetically?  By category?  Sorted by a variable value?
    * Should the data be averaged?
    * If you aggregate or average the data, are you smoothing out noise in the data, or are you masking signal?
* Is the plot a faithful representation of the data?  Don't lie.

### When you're done...
If you feel okay sharing your sketch with the class, please submit it to this [folder](https://drive.google.com/drive/u/0/folders/0B0feBm9JeWrZT1F3eWMxZzB0S3c). It doesn't have to be finalized, and it won't be shared beyond the class.
