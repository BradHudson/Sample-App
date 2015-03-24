### This is now the Job Swiper app deployed to heroku: https://pure-oasis-6367.herokuapp.com/projects

In my Job-Swiper Repo, I had a ton of problems with the gemfile and items that were preventing the deploy. From that, I believe it's
important to deploy as early as possible to avoid those mistakes.

######What this currently does:

1. Uses the CB API to get back job results based on keywords and location
2. Displays the results individually
3. Allows the user to swipe on a mobile device between jobs
4. Looks good on Mobile!

######Features needing implementation:

1. Better UI for search screen
2. When swiping left or right, the job is removed and marked as a 'yes' or 'no' much like Tinder
3. A conclusion or summary of which jobs were marked as 'yes'
4. Move title of app to middle
5. Move icon bar button to the far left
6. Clicking icon bar button slides out a panel showing navigation
7. Place 'messages' bubble button on the far right which will bring you to your messages page
8. Add Instructional Arrows to the left and right of screen when user first loads the page indicating where to swipe
and what will happen.
9. Once the user swipes, the instructional messages go away
10. If the user allows us to use location, use that to search
11. Possibly have the user set in settings what jobs they are interested in so they skip the search screen and go
right to jobs.

######Done

1. More details about each job