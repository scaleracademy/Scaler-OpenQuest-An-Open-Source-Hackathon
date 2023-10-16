# Problem Statement: A professional profile building website

# Motivation

People create openfor.work profiles as their personal portfolio aggregator. We cater to a few broad categories of people that startups largely hire for

- Developers
- Designers
- Content Specialists
- Product Managers


An openfor.work profile would first of all be very easy to aggregate existing portfolios. People already use StackOverflow, Github, Behance, Dribbble etc for work portfolio. We must allow easy and seamless integration with those (to start with add link to those profiles, but eventually, do proper authentication via API and show details).

In addition, there should be native support to add additional projects to showcase, and support to add a 1min video testimonial.

The profiles should be able to be denoted as open for part time, full time, gigs or internships.

We are solving for the supply side aggregation here. So the goal is curate profiles and provide a big collection to those who hire. This platform is for listing portfolios, and not listing jobs.

# Aggregations
The 3rd party accounts we must integrate are -

Github (for developers)
StackOverflow (for developers)
CodeChef/LeetCode/HackerRank (for developers)
Dribbble (for designers)
Behance (for designers)
Figma (for designers)
LinkedIn
YouTube
Medium
HashNode (for Developers)
Dev.To (for Developers)


# User Stories
Onboarding (profile builders / job seekers)

User Stories
Onboarding (profile builders / job seekers)
Landing page has a "Are you openfor.work ? " CTA

Clicking on that takes to simple tap-able process with as little manual information needed as possible.

Step 1 - import from LinkedIn - or else enter name, email, contact no, profile photo

Step 2 - tap and select from icons - "I am good at..." -

Development
Design
Content
Marketing
Depending on what was selected previously we ask for following connections (through API, or initially just submit links)

Development
Github
StackOverflow
LeetCode
Design
Behance
Dribbble
Figma
Content
Medium
Personal Blog
Marketing
Facebook
Instagram
Youtube
** People can add other type of profiles from their choses profession (developer can add a Medium blog) later through account settings. In onboarding flow the above onces are what are suggested.

Add a < 3min video that covers

Who are you ?
Professional achievements till now ?
What do you like to work on
Once profile is built, Projects can be added. Each project will have these fields

Title* (100 char)
Description* (2000 char)
Cover Images* (min 1, max 4)
Links
Demo Video



