# Startup-path
I got myself caught in the cycle of making a new application and doing all the same steps over and over again, like opening a domain, setting up a git, coming soon page etc. So I decided to make a document to collect all the steps I usually go through in order to setup a new startup.

## How to use
You can fork the repository and check the items once you have completed them. You can customise the document to your particular needs. I tried to put everything into logical order.

## New startup check-list

Customise this list to your needs.

### Stage #1 - preparation
- [ ] Choose a name (choose a short, brandable name. If you get stuck with the name, use the following resources to generate one, along with the logo: https://namelix.com/, https://businessnamegenerator.com/)
- [ ] Choose a logo for the company, you could design one yourself by finding the icon at https://www.flaticon.com/ or ordering one at https://www.fiverr.com/ (the prices are quite low, about 5$ for a decent logo)
- [ ] Register a domain. I use https://namecheap.com for domain management
- [ ] Setup a coming soon page. I try not to setup any server at this point, so the method that worked for me is the combination of Heroku and Netlify. Netlify offers awesome CDN and one-click deployment, Heroku offers free one-click deployment for backend. For the mailing list I use Airtable, because it offers the level of customisation I need and the API is pretty easy to use.
- [ ] Setup a domain email. There are lots of services to setup a free email service for your domain. I personally use https://biz.mail.ru, because they offer unlimited number of emails, for example for future employees or bots.
- [ ] Setup social media. You should setup your social media on a separate email, like contact@mystartup.com, it will help to unify all the emails into one stream.
- [ ] Setup a github repository for your projects. I personally use gitlab for multi-repository projects, because they offer free-to-use groups, where I can setup my frontend, backend etc. Additionally, I use docker for all my projects, so gitlab automatically detects Dockerfile and builds my project on each commit. Container registry from Gitlab is really simple to use. 
- [ ] Setup a task board. There are dozens of task boards, I prefer to use Trello for all my projects, they offer lots of templates to get started with. 
- [ ] Setup a communication channel between your team-members. There are lots of options, but obvious one is Slack. These days I use Telegram, simply because they are less restrictive than Slack (like free calls and unlimited history).

### Stage 2 - Development
- [ ] If your application requires a good UI, spend time and find good CSS framework, I try to use multiple frameworks to experiment with designs. Some of my favourites: Material UI, Semantic UI, Ant.Design, UIKit
- [ ] Try to use latest frontend technologies - SPA, PWA etc. My personally favourite frontend framework is Vue.JS. It is really simple to get started with than Angular or React.
- [ ] Choose a backend stack. For prototyping stage I would recommend Python with Django or NodeJs with Express. If you want to both iterate fast and have your tecnhical debt to minimum, I would recommend using GoLang, as it offers both development speed and performance. However, it will be harder to get started with if you are looking for a fast solution.
- [ ] Use Postman to document your API, it will be both useful for frontend development and will setup a future foundation.

### Stage 3 - Launch
In progress
