# Check in - 27 May 2019

I always intend to have a check in at least once a week, but that hasn't happened in awhile. Anyways, here's my latest check in on my 6 startups in 6 months effort.

**Reminder for overall goal: Develop a USD 20 million business by 2038**

Overall status: Currently in middle of development of projects #3 and #4. Project #1 has good product-market fit, while Project #4 has some fit. Remaining 2 projects don't have fit yet. On progress to finish 6 in 6 challenge by end of July.

## [Project 1](https://burningvpn.com)
### Current status
- Paid users last 30 days: 9
- Users currently on trial: 3
- I think we can say that we've found product-market fit for this. This is an established industry.
### Next steps
- Automate creating new credentials (in progress)
- Build marketing engine to start bringing customers in regularly and iterate the sales funnel
### Keep in view
- Create internal dashboard for usage metrics

## [Life Flips](https://itunes.apple.com/us/app/life-flips/id1454193608?mt=8)
### Current status
- No progress, minimal downloads
- No product-market fit
### Next steps
- Re-setup landing page! Went down after I shut down carrd.co
- None for now, will focus on this after 6 in 6 is finished
### Keep in view
- Backlog of features I want to build. See [LifeFlips Todo List](Life%20Flips%20Todo%20List.md)

## [My Money](https://pfm-project-2.webflow.io)
### Current status
- Built basic landing page, though incomplete
- Intend to "soft launch" with friends and family to gather feedback in the immediate future.
### Next steps
- Fix up landing page for public
  - Include road map for future features
- Build out simple functionality: Record balances in different currencies
  - Requires login functionality
  - Auto convert to your currency
- Build out additional functionality: Drag raw transaction CSV and automatically saves clean CSV to your desktop
  - Start with Alipay, BankWest, Commbank, Citi (AU), and CommSec (securities)
  - Includes simple auto-categorization
### Keep in view
- Continue working with potential users directly to build specific functionality for them (customer-driven innovation)
- Build database for securities so we can help track stock trading performance
  - Later, expand to other investment classes (bonds, mortgages, etc.)
- Continue to think about tax planning

## [101 Days Challenge](https://101-days-challenge.webflow.io)
### Current status
- Created 2nd 101 days challenge group. Users are very active. Possibly semi-product-market fit.
- Created basic landing page, though messaging can be clearer 
- Currently I spend 5 min a day to update Airtable with logs and send out dashboard
### Next steps
- Create 5 more groups. Can be single focus (on exercise), or other focus
- Send out survey after 25 days in fitness. See if people find it useful
### Keep in view
- Find a way to automate creating groups from link
- Continue to think about:
  - How to market this? Focus on one type first - fitness? Or go widely across multiple needs?
  - How to automate scraping messages from chat into database
- Automate creating dashboard message

## Podcast app (Project #5 - target 30 June launch)
- Tweet chain describing my thoughts on this: [Twitter thread](https://twitter.com/youngchingjui/status/1132939172258361345)
- Target to start early June
- iOS first, or maybe learn React for this?

## Project #6 - Not decided yet
---
## Other side projects
There's a number of other things I'm doing on the side. Some are tools, some are just slides I need to make. I intend to publish everything I do here so that it doesn't just get lost on my computer. Though I don't think any of the tools really warrant to be a full product. But I'll publish them and see if there's a need for them regardless. Perhaps each of these projects deserve a blog post each?

### Preparing for talk on 11 June
[My current draft slides](https://www.icloud.com/keynote/0xaqO1WG8USWKtPbY61quP7tg#6_startups_in_6_months)

I was invited to share my 6 startups in 6 months project to people looking to go down the entreprenuership path. It'll be held at my co-working space on 11th June.
Todo: 
- Develop slides and my story for talk
- Prepare materials to teach Lean Startup methodology

### [TogglToCalendar](https://github.com/youngchingjui/TogglToCalendar)

I use a program called Toggl to help me track my time on the projects I'm working on. I'd like to see these logs recorded on my Google Calendar. Currently, I've set up a Zapier to automatically transfer the data from Toggl to Google Calendar, but I hit my limit of 100 "transfers" every month very quickly. I'm writing the code to automatically do this myself without using Zapier.


### Combine GCP costs on BigQuery across multiple accounts
I have multiple billing accounts on Google Cloud Platform. It's difficult to get an aggravated view of my server costs. I'm trying to configure my BigQuery databases (where my GCP transactions are stored) to merge together into a single database.

### Track Outline usage statistics and save to BigQuery
Issue: I don't have accurate visibility of the usage metrics on my servers. I'd like to build tracking capabilities so I can more accurately analyze per-customer costs. It would also give me the option to build pricing structures around data usage.
I've set up a function on Google Cloud Functions to accept incoming usage statistics and save them to BigQuery, but I don't know how to send the data from my server to the Cloud Function. 

### [Github contribution tracker](https://github.com/youngchingjui/github-contribution-tracker)
I've built a simple landing page that allows you to add a user's Github username, and you'll get a dashboard of their contribution history. 
Still requires some Javascript coding.
No future plans for this yet. Just a fun project

### Trading bot
Will have to review my old code on this. Will revive this in the future after 6 in 6.

### Update [Young & AI](youngandai.com) blog page
I want to build a refreshed homepage using Webflow, since I am paying for membership right now.
I want to build a way to publish blogs from Markdown files uploaded to Github