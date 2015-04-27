Hashtag Palindrome Coding Challenge
===================================

Write a single page web app that uses the Twitter API to determine the number of palindromic strings that can be created from each hashtag in a given user's recent tweet history.

Details
-------
The web application should be a single page app. Given a Twitter handle, the app should retrieve the last 50 tweets by that user and extract any hashtags. The app should then show the list of unique hashtags and the number of palindromic strings that can be created using the letters in each hashtag. Results should be sorted by the latter, highest to lowest. For any values >= 1B, the value should be displayed in scientific notation.

A valid palindromic string is one that uses only the letters in the given hashtag, and is the same length as the given hashtag. Each letter can be used more than once, and not every letter must be used. For example, given the hashtag "#hashtag", "aaaaaaa" and "hhagahh" are valid, but "aaa" and "hhsagtt" are not.

Constraints
-----------

* Choice of languages and frameworks is open.
* The layout should match the provided screenshots as closely as possible.
* Submissions should be made available on GitHub.
