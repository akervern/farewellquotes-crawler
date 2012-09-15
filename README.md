# farewellquotes-crawler

## Overview

This scripts crawls the given URL from [farewell-quotes](http://farewell-quotes.com//) to extract messages and post them to the specified sosmessage API URL.

Sample usage:

    ./farewellquotes-crawler.rb -u http://farewell-quotes.com/farewell-love-quotes/ -s http://localhost:3000 -c 505429e5e4b053989ee43a82

Full options:

    Usage: farewellquotes-crawler.rb [options]
    -u, --messages-url URL           The unecartedevoeux category url
    -s, --sosmessage-url URL         The sosmessage API url
    -c, --category-id CATEGORY_ID    The category id where to post the messages
    -m, --max-characters MAX         MAX characters of the message
    -n, --dry-run                    Don't actually post the messages, only display them
    -h, --help                       Display this screen
