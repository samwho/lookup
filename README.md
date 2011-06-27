# Install

To install, you will need to install 2 dependency gems:

    gem install wordnik
    gem install colored

Then download the `lookup` script file. Then make the `lookup` file executable:

    cd /path/to/lookup
    chmod +x ./lookup

Then you will need to acquire an API key from http://developer.wordnik.com,
open up the lookup script and modify this line:

    config.api_key = 'your api key here'

Inserting your API key where necessary. Then you're all set!

# Usage

Using lookup is dead simple. First, either make sure the lookup script is
in your PATH or make sure you are in the same directory as it, and then
usage is as follows:

    lookup cat

This will lookup the word "cat". If you want some examples of the word
used in context, supply the -e or --examples flag:

    lookup cat -e

And that's it! Enjoy.
