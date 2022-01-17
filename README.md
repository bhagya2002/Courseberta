<p align="center">
  <img width="128" height="128" src="website/static/shield.svg">
</p>
<h1 align="center">Courseberta</h1>

Courseberta is here to help you get your questions answered. Make an account and ask/answer questions all in one place. Like other's answers if you agree and check out a list of profs teaching the current or upcoming semester for any course taught at the UofA.

The devpost for the project can be seen [here](https://devpost.com/software/courseberta).

## Inspiration
As students, we want to be able to quickly learn about the courses we are taking and ask about them. Things like Reddit and Discord, can technically do it, but they do it in an unorganized manner. These websites and apps are not laid out in an organized manner and can require digging in order to find a specific post. Our webapp organizes all the courses out in a neat manner and keeps questions attached to the course the question is about. This way, students don’t have to go digging around to find posts about previous topics, it should be exponentially easier to find.

## What it does
Our app allows students to ask, answer, and view questions on specific courses. All of the questions will be attached to a specific course, this makes it much easier for students to find questions and answers that are asked about the course they are interested in. We also made it so that students can check the ratings of professors that are currently teaching the course they are interested in. These ratings out of 5 are the rating students gave to professors in ratemyprofessors.com.

## How we built it
We used HTML, CSS, and Bootstrap 5 for the front end of the website. For the backend, we used Flask, Python, and some Javascript. We also used Jinja to implement aspects from the backend to the frontend. We built the webapp using a VSCode extension called LiveShare. This allowed all of us to work together on the same github in real time.

## Challenges we ran into
When making the accounts using our University of Alberta emails, our IP’s got blacklisted. We had to send in a request and explain our situation, and eventually got unbanned around 11PM. VSCode liveshare would also constantly reformat our code after saves. It would also randomly revert back to older versions of the code. LiveShare would also randomly write random code that we were unable to delete. For the JSON files, it took about 30 minutes just to process the files because of how much information it contained. It was also difficult to create such a complex application on a single webpage since we used models to display all of our information.

## Accomplishments that we're proud of
We are very proud of the overall complexity of our webapp. We think we managed to input a large amount of functionality in the given time frame. We are also very proud of the overall look of our website and the minimalistic design it has.

## What we learned
We learned a lot about web scraping and backend development with javascript.

## What's next for Courseberta
We want to host the website because it is currently only hosted locally. We could also expand to other universities and their courses. We could also allow students to rate the professors, since our website currently just takes the information from ratemyprofessors.com

## Why our webapp applies to the Twilio usage
Our website is specifically for students. This means we needed to use Twilio to verify the emails of University of Alberta students. We think that overall, this makes our website much cleaner and organized. This makes Twilio crucial in our webapp.
