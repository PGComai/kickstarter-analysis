# Kickstarting with Excel

## Overview of Project

### Purpose

Our friend Louise had us check out some Kickstarter data to help her fund *Fever*,
her play, on the platform. We analyzed a dataset containing information about thousands
of Kickstarter campaigns. This information included funding goals, campaign outcomes,
genre, date, and more. We used this data in order to help Louise understand how she
might best set up her campaign for success.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Here is a line chart showing how campaigns for theater projects fared based on their
launch dates.

/kickstarter-analysis/resources/Outcomes_vs_Goals.png

An immediate conclusion we can draw is that the month of May is great for launching
your theater campaign. This advantage slowly decreases until August, at which point 
the odds return to their March/April levels. We can also conclude that December
is the worst time, when the odds of a successful campaign don't seem much better
than those of a failed one.

### Analysis of Outcomes Based on Goals

Up next, a line chart comparing campaign outcomes according to how much money they
asked for, the fundraising goal. The dotted line represents the percentage of projects 
within the given funding goal.

insert link here

The odds of fundraising success (blue line) trend downward as the funding goal
increases, except for the $30,000 to $45,000 range, where it goes back up.
While this is what the data show, I believe that Louise should not let that
part of the chart influence her decision. Rather than assuming a goal of $35,000
would have better odds than a goal of $25,000, I think it's more likely that
some other factor is causing the increased success. It could be that those projects
fall into some different category, such as having increased publicity from the onset
or some sort of celebrity backing. It's also possible that the small percentage of
campaigns with such large goals are less predictable than those with smaller ones.

### Challenges and Difficulties Encountered

When calculating the outcomes based on funding goals, I spent a while trying to
figure out why my formula was returning 0 for the entire 'number canceled' category.
It turned out that I was spelling canceled wrong, but more importantly, it also turned
out that there really were 0 cancelled projects in the 'plays' subcategory. This is 
great news for people who want to fund a play and don't want to end up cancelling it.

## Results

- Louise should see that there are good and bad times to launch her campaign. May looks
to be the best, while December is clearly the worst.

- As for funding goals, less is more. The majority of the data shows a downward trend
in campaign success as the goal increases.

- A limitation of this dataset is the fact that we can't pin the success of a campaign
solely on the statistics we are given. The 'blurb' column could be very important,
but we can't really put that on a chart. 

- I would like to see how 'staff_pick' and 'spotlight' affect the outcomes of the
campaigns. Maybe the inconsistency in the Outcomes Based on Goals analysis could be
explained by those.

