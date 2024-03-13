Goal:
Your user try to click a button in exactly 3 seconds

Steps:
Step 1: User navigates to your site Url via GitHub pages
Step 2: Large button saying Start
Step 3: User clicks button and the button text says Stop
Step 4: After the user thinks 3 seconds has elapsed they click the button again.
Step 5: The user is provided the elapsed time in seconds. The button text returns to Start. If the elapsed time is 3 seconds then display green indications, if the time is within +/- .2 seconds display blue indication, if the elapsed time is within +/- .5 seconds display yellow indication and anything greater is red.

The user can make multiple attempts. Allow the user to OPTIONALLY view more each of the following:
A summary of each attempt's result. (attempt number, start time and stop time)
A summary of the results (total attempts, min, max, avg)

Include a JavaScript chart.  https://flatlogic.com/blog/best-19-javascript-charts-libraries/Links to an external site.

Utilize bootstrap
4 seconds should be a configurable constant/global variable.

Hint: To capture the current time in milliseconds use the JavaScript Date() object.
