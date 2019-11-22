# iffdigest

Revamped version of code and ideas by Andrew C. Bulhak. See [iffdigest](https://github.com/andrewcb/iffdigest) for the original.

Much of my focus was on hardening the walk of the chunks so that a failure would not crash the program. To that end, I made
sure that all access into the data were first validated to be safe, and to throw an exception if it was not. I also tried to 
reduce the amount of casts being done, and when necessary make them C++ casts rather than old-school C ones. Finally, I added
commentary and renamed to try and improve the look-and-feel of the API.