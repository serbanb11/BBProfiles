# BBProfiles
Burp Bounty (Scan Check Builder in BApp Store) is a extension of Burp Suite that improve an active and passive scanner by yourself. This extension requires Burp Suite Pro.

BurpBounty scanner: https://github.com/wagiro/BurpBounty
* Author Twitter: @egarme

All profiles are intended to find API keys, based on:
https://twitter.com/Jhaddix/status/1113947380523589632
https://github.com/alessandrodd/api_key_detector

test.html - test file for rules

## Profiles
### Passive Scanner
| API key | RegEx |
| ------  | ----- |
| AmazonAwsSecretKey | [0-9a-zA-Z/+]{40} |
| AWSAPIID | AKIA[0-9A-Z]{16}<br>AAGA[0-9A-Z]{16}<br>ACCA[0-9A-Z]{16}<br>AGPA[0-9A-Z]{16}<br>AIDA[0-9A-Z]{16}<br>AIPA[0-9A-Z]{16}<br>ANPA[0-9A-Z]{16}<br>ANVA[0-9A-Z]{16}<br>APKA[0-9A-Z]{16}<br>AROA[0-9A-Z]{16}<br>ASCA[0-9A-Z]{16}<br>ASIA[0-9A-Z]{16} |
| BitlyClientID | [0-9a-zA-Z_]{5,31} |
| BitlySecretKey | R_[0-9a-f]{32} |
| FacebookAPI | [0-9a-f]{32} |
| FlickrClientID | [0-9a-f]{32} |
| FlickrSecretKey | [0-9a-f]{16} |
| FoursquareAPI | [0-9A-Z]{48} |
| LinkedinClientID | [0-9a-z]{12} |
| LinkedinSecretKey | [0-9a-zA-Z]{16} | 
| TwitterSecretKey | [0-9a-zA-Z]{35,44} |
| MailgunSecretKey | key-[0-9a-f]{32} |
| SendgridSecretKey | SG[.][0-9a-zA-Z-_]{22}[.][0-9a-zA-Z-_]{37}-[0-9a-f]{4}-[0-9a-zA-Z]{5} |
| GoogleAuthSecretKey | [0-9a-zA-Z-_/]{70}[.] |
| MailchimpSecretKey | [0-9a-f]{32}-us[0-9]{1,2} |
| GithubClientID | [0-9a-f]{20} |
| GithubSecretKey | [0-9a-f]{40} |
| StripeSecretKey | sk_live_[0-9a-zA-Z]{24} |
| GoogleAPI | AIzaSy[0-9a-zA-Z-_]{33}<br> |
| SlackSecretKey | xoxb-[0-9]{11}-[0-9a-zA-Z]{24} |
| BeepboopSecretKey | [0-9a-f]{32}-[0-9]{9} |
| MashapeSecretkey | [0-9a-zA-Z]{50} |
| GitlabSecretKey | [0-9a-zA-Z]{20} |
| HerokuapiSecretKey | [0-9a-f]{8}-[0-9a-f]{4}-[0-9a-f]{4}-[0-9a-f]{4}-[0-9a-f]{12} |
| MattermostSecretKey | [0-9a-z]{26} |
| RecaptchaSecretKey | 6L[0-9a-zA-Z-_]{38} |

