Hosted on GitHub Pages---
layout: default
---


mb today dev started from Jan



# January

* Website server setup.
* DNS registration completed.
* SSL registration completed		
* AWS SES mail server setup
* Basic website setup completed
* Added features such as Reaction, Gamification, Follow, and Post Voting

## Known issues
* SSH needs to be migrated
* Server firewall is not established
* MaxMind is not configured

# February

* Started learning Discourse component development
* Completed development of wechat-tip-qrcode 0.1
* Tested Zapier and Twilio automation solutions
* Tested AWS Lambda Gateway automation solution, successfully integrated SES functionality
* Added OAuth options such as Discord, Google, and Apple

## Known issues:
* Tip-qrcode lacks a review mechanism
* Twilio and Zapier automation solutions have low feasibility
* Default webhook lacks user information
* Apple OAuth is missing API key and needs to be disabled

# March-April

* Learned how to develop Discourse plugins
* Completed development of PaymentLink 1.0
* Developed customer service features for PaymentLink
* Successfully configured MaxMind
* Successfully configured Perspective API functionality
* Developed and tested house ads

## Known issues:
* PaymentLink encounters errors due to website CSP
* PaymentLink lacks inventory management features
* Customer service query feature consumes a lot of bandwidth and takes more than 3 seconds, needs optimization
* Product pages need optimization


# May

* Completed development of categories-navbar-main 1.0
* Completed development of ad-component 1.0
* Optimized CSP issues for PaymentLink
* Successfully migrated SSH
* Successfully established the website firewall
* Optimized the PaymentLink product page

## Known issues:
* Ad-component throws a timeout error when the image URL is empty
* Tobar-categorise uses an outdated Discourse widget component and needs updating


# June

* Changed the theme to "Grace"
* Renamed the website to "Manitoba Today" and updated the SSL certificate
* Completed DNS migration
* Upgraded the server, reduced Unicorn workers, and minimized the occurrence of 429 errors
* Established the component "cnbbs-custom"
* Used the "custom homepage for group" component to set the new homepage as c/1-news
* Fixed a potential site crash caused by the categories nav
* Made extensive changes to website settings
* Added keyword moderation

## Known issues:
* The "Grace" theme requires extensive detail modifications
* The "cnbbs-custom" component lacks mobile support
* The appearance is not optimized for different desktop resolutions
* House ads are partially blocked by ad-blockers


# July

* Deployed AWS Cloud CDN
* Finalized and tested the ad payment solution
* Fixed subscription bugs
* Completed development of the topic-limitation plugin 1.0
* Completed development of sidebar-tagbox 1.0
* Fixed the overall website font
* Made extensive theme styling changes

## Known issues:
* Tag color conflicts with sidebar-tagbox
* User feedback interface is unattractive
* The advanced left-nav in the documentation section has a bug, causing it not to display


# August

* Changed the theme to "Default"
* Added and modified the top search functionality
* Updated CNBBS-custom to add mobile support
* Created "cnbbs-color" and "cnbbs-width-control"
* Completed homepage styling implementation
* Updated website text
* Adjusted the display of sidebar security level
* Added support for Bilibili video onebox

## Known issues:
* Ad-component needs to support new widths
* Default ad display requires adjustments
* There's a bug with the supported length of form-template

# September

* Tested RSS polling functionality and identified RSS sources
* Attempted local AI implementation for RSS content
* Tested OpenAI API and BeautifulSoup for scraping and translation
* Tested native Discourse AI
* Fixed a bug with maximum input length in form-template

## Known issues:
* Local AI CUDA computation is causing memory overflow
* Discourse AI requires server GPU CUDA computation, exceeding the original budget
