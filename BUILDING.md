## BUILDING

1. To build the HNES extension, clone repository locally:

    git clone https://github.com/d5p/HNES.git HNES.safariextension

* In Safari, open Extension Builder [Develop->Show Extension Builder]

* Create a new extension by adding the checked out extension folder from above.

*   Required Extension Details:
    #### Extension Info:
	    Display Name: HNES 
        Author: <name>
        Description: Hacker News Enhancement Suite
        Website: <website>

    #### Extension Details:
        Bundle Identifier: <bundle identifier>

    #### Extension Versions:
        Display Version: 1.0
        Bundle Version: 1

    #### Extension Website Access:
        Access Level: Some
        Allowed Domains:    news.ycombinator.[com|net|org]
                            hackerne.ws
        Include Secure Pages

    #### Extension Storage:
        Database Quota: 1 MB

    #### Injected Extension Content:
        End Scripts:
            js/jquery-1.7.2.min.js
            js/linkify/jquery.linkify-1.0-min.js
            js/linkify/plugins/jquery.linkify-1.0-twitter-min.js
            js/hn.js

        Style Sheets:
            style.css

* Install extension directly from Extension Builder by selecting 'Install', or build an installable extension for distribution by selecting 'Build Package'.
