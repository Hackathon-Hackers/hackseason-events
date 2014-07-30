HackSeason - Events
=========

This repo is meant for students to add their event to www.hackseason.com. Please follow the guidelines for making a pull request to the repo!

###Format

  1. name - event name
  2. description - 100 word limit
  3. thumbnail - 100 x 100px PNG (300DPI)
  4. banner - 500 x 150px PNG (300DPI)
  5. start_date - YYYY-MM-DD
  6. end_date - YYYY-MM-DD
  7. website_url - must be a full url
  8. register_url - must be a full url
  9. support_email
  10. sponsor_email
  11. facebook - page name
  12. twitter - twitter handle
  13. location - full address
  14. travel_reimbursement - "full", "none", or $amount.
  15. event_size - # of people
  16. hs_hackers - "true" or "false"
  17. keywords - 5 keyword max


###Example
```
[
  {
    "name": "Cal Hacks",
    "description": "Cal Hacks",
    "thumbnail": "./assets/calhacks_thumbnail.png",
    "banner": "./assets/calhacks_banner.png",
    "start_date": "2014-10-03",
    "end_date": "2014-10-05",
    "website_url": "https://www.calhacks.io",
    "register_url": "https://apply.calhacks.io",
    "support_email": "team@calhacks.io",
    "sponsor_email": "sponsor@calhacks.io",
    "facebook": "calhacks",
    "twitter": "calhacks",
    "location": "210 Stadium Rim Way, Berkeley, CA 94720",
    "travel_reimbursement": "full",
    "event_size": "1200",
    "hs_hackers": "true",
    "keywords": [
      "UC Berkeley",
      "University of California",
      "California",
      "Berkeley"
    ]
  }
]
```

###Rules
1. Test all your URLs and make sure they are valid.
2. Links must all be direct links. No redirects allowed.
2. Validate your JSON with using [JSONLint](http://jsonlint.com/).
3. Pictures must be in PNG format in the size specified at 300DPI.
4. Do not try to do anything to make your event stick out on the page!
