# Placement Sprint

A 16-week study planner for campus placements and AI/ML, built for a final-year EIE student. It opens on today's topics, gives each topic its own notes page, and asks for a rating after every topic.

## Features

- Welcome screen with a ring of all 112 days showing done, missed and today.
- Today's topics pop up as cards: aptitude, main subject, core subject, coding and jobs.
- Each topic opens a notes page split into sections, with practice questions and answers.
- A rating after each topic: understanding from 1 to 5 stars and how hard the notes felt.
- Topics rated hard get a revision task on the next day.
- Missed tasks stay on top until they are finished, and a reminder shows after the chosen time.
- Journey, Progress and Settings tabs.

## Run it

Open `index.html` through any static web server, or publish the repository with GitHub Pages. Progress is saved in the browser's local storage on each device.

## Notes

Notes live in the `notes` folder, one Markdown file per task, named by task id. The first task of day 1 is `d0-0.md`, the second is `d0-1.md`, and day 2 starts at `d1-0.md`. Days 1 and 2 are included.

The Claude-hosted version of this site writes notes for new topics with Claude and adapts them to your ratings. That feature does not work on GitHub Pages, so add more notes as Markdown files here.
