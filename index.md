


mb today dev started from Jan


| date       | commit |         
|:-------------|:------------------|
| Sep 16       | test deepll and aws cloud translation api | 
| Sep 13       | Test Gemini ai api for translation | 
| Sep 12       | rebuild cnbbs footer | 
| Sep 11       | Tested OpenAI API and BeautifulSoup for scraping and translation | 
| Sep 9        | Fixed a bug with maximum input length in form-template   | 
| Sep 4        | Attempted local AI implementation for RSS content      | 
| Sep 3        | update server | 
| Sep 2        | Tested native Discourse AI | 

## Known issues:
* Local AI CUDA computation is causing memory overflow
* Discourse AI requires server GPU CUDA computation, exceeding the original budget
* Gemini ai is using turbo 3.5, and cloud studio is hard to configue



| date       | commit |         
|:-------------|:------------------|
| Aug 25       | Added support for Bilibili video onebox |
| Aug 22       | homepage styling implementation |
| Aug 20       | Adjusted the display of sidebar with new component |
| Aug 19       | Adjusted the display of sidebar security level |
| Aug 15       | Updated CNBBS-custom to add mobile support |
| Aug 12       | Changed the theme to "CNBBS custom", "width control" |
| Aug 8        | Updated website text |
| Aug 5        | Added and modified the top search functionality |
| Aug 2        | Changed the theme  "CNBBS custom" |
| Aug 1        | Changed the theme to "Default" |

## Known issues:
* Ad-component needs to support new widths
* Default ad display requires adjustments
* There's a bug with the supported length of form-template
* doc name need to be changed, but no where to change, need to check referance



| date       | commit |         
|:-------------|:------------------|
| Jul 31       | theme styling changes |
| Jul 30       | theme styling changes |
| Jul 29       | theme styling changes for lobby |
| Jul 28       | color change |
| Jul 26       | theme styling changes |
| Jul 25       | Fixed the overall website font |
| Jul 24       | Completed development of sidebar-tagbox 1.0 |
| Jul 18       | Completed development of the topic-limitation plugin 1.0 |
| Jul 11       | Fixed subscription bugs |
| Jul 8        | Finalized and tested the ad payment solution |
| Jul 4        | configure AWS S3 for further CDN use like ads |
| Jul 2        | Deployed AWS Cloud CDN |

## Known issues:
* Tag color conflicts with sidebar-tagbox
* User feedback interface is unattractive
* The advanced left-nav in the documentation section has a bug, causing it not to display




| date       | commit |         
|:-------------|:------------------|
| Jun 28       | keyword moderation, setup new api key for paymentlink  |
| Jun 26       | "CNBBS custome" theme styling changes |
| Jun 25       | Fixed a potential site crash caused by the categories nav |
| Jun 19       | Used the "custom homepage for group" component to set the new homepage as c/1-news |
| Jun 14       | Established the component "cnbbs-custom" |
| Jun 11       | Upgraded the server, reduced Unicorn workers, and minimized the occurrence of 429 errors |
| Jun 7        | Completed DNS migration |
| Jun 4        | Renamed the website to "Manitoba Today" and updated the SSL certificate |
| Jun 2        | Changed the theme to "Grace" |

## Known issues:

* The "Grace" theme requires extensive detail modifications
* The "cnbbs-custom" component lacks mobile support
* The appearance is not optimized for different desktop resolutions
* House ads are partially blocked by ad-blockers



| date       | commit |         
|:-------------|:------------------|
| May 31       | theme styling changes, margin, left nav, colors |
| May 28       | Added BBCode support component |
| May 26       | Optimized the PaymentLink product page |
| May 21       | established the website firewall |
| May 17       | Successfully migrated SSH |
| May 15       | Optimized CSP issues for PaymentLink |
| May 13       | Completed development of ad-component 1.0 |
| May 6        | Completed development of categories-navbar-main 1.0 |

## Known issues:
* Ad-component throws a timeout error when the image URL is empty
* Tobar-categorise uses an outdated Discourse widget component and needs updating



| date       | commit |         
|:-------------|:------------------|
| Apr 30       | changed paymentlink table to discourse native table, add mobile support version |
| Apr 26       | Developed and tested house ads |
| Apr 22       | Successfully configured Perspective API functionality |
| Apr 19       | configured MaxMind |
| Apr 18       | Developed customer service features for PaymentLink |
| Apr 4        | Completed development of PaymentLink 1.0 |
| Mar 1        | start to Learn how to develop Discourse plugins |

## Known issues:
* PaymentLink encounters errors due to website CSP
* PaymentLink lacks inventory management features
* Customer service query feature consumes a lot of bandwidth and takes more than 3 seconds, needs optimization
* Product pages need optimization
* perspective Api will cause js uncaught error



| date       | commit |         
|:-------------|:------------------|
| Feb 28       | add google font, mordern category group box, Exerpt, thumbnails and other theme components |
| Feb 26       | add automation and assign plugin, tested |
| Feb 25       | Added OAuth options such as Discord, Google, and Apple, tried wechat |
| Feb 22       | Tested AWS Lambda Gateway automation solution, successfully integrated SES functionality |
| Feb 15       | Tested Zapier and Twilio automation solutions |
| Feb 13       | Completed development of wechat-tip-qrcode 0.1 |
| Feb 1        | Started learning Discourse component development |

## Known issues:
* Tip-qrcode lacks a review mechanism
* Twilio and Zapier automation solutions have low feasibility
* Default webhook lacks user information
* Apple OAuth is missing API key and needs to be disabled
* wechat auth need qq and extra IPC 



| date       | commit |         
|:-------------|:------------------|
| Jan 31       | made some future plans |
| Jan 30       | Added features such as Reaction, Gamification, Follow, and Post Voting |
| Jan 29       | Basic website setup completed |
| Jan 25       | SSL registration completed, AWS SES mail server setup |
| Jan 24       | Website server setup, DNS registration completed. |

## Known issues
* SSH needs to be migrated
* Server firewall is not established
* MaxMind is not configured



