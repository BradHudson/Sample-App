# This is now the Job Swiper app deployed to heroku: https://pure-oasis-6367.herokuapp.com/projects

In my Job-Swiper Repo, I had a ton of problems with the gemfile and items that were preventing the deploy. From that, I believe it's
important to deploy as early as possible to avoid those mistakes.

What this currently does:

-Uses the CB API to get back job results based on keywords and location
-Displays the results individually
-Allows the user to swipe on a mobile device between jobs

Features needing implementation:

-Better UI
-More details about each job
-When swiping left or right, the job is removed and marked as a 'yes' or 'no' much like Tinder
-A conclusion or summary of which jobs were marked as 'yes'