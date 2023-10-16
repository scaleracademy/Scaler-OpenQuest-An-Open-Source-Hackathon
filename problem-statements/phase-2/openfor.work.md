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
## Onboarding (profile builders / job seekers)

1. Landing page has a "Are you openfor.work ? " CTA

2. Clicking on that takes to simple tap-able process with as little manual information needed as possible.

3. Step 1 - import from LinkedIn - or else enter name, email, contact no, profile photo

4. Step 2 - tap and select from icons - "I am good at..." -

i. Development
ii. Design
iii. Content
iv. Marketing

5. Depending on what was selected previously we ask for following connections (through API, or initially just submit links)

i. Development
- Github
- StackOverflow
- LeetCode

ii. Design
- Behance
- Dribbble
- Figma

iii. Content
- Medium
- Personal Blog

iv. Marketing
- Facebook
- Instagram
- Youtube

**People can add other type of profiles from their choses profession (developer can add a Medium blog) later through account settings. In onboarding flow the above onces are what are suggested**

6. Add a < 3min video that covers

i. Who are you ?
ii. Professional achievements till now ?
iii. What do you like to work on

7. Once profile is built, Projects can be added. Each project will have these fields

i. Title* (100 char)
ii. Description* (2000 char)
iii. Cover Images* (min 1, max 4)
iv. Links
v.Demo Video



