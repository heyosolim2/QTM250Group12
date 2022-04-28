# A Look into the Google Cloud Platform’s “Vision” API for Optical

Character Recognition
We decided to look into the efficacy of the Machine Learning API: Vision found in the
Google Cloud Platform (GCP). Its ability to recognize characters can be quite useful if proves it is
capable of doing so across three different types of text: Webpage, Scanned, and Handwriting.
While “webpage” and “scanned” text may be slightly easier for the API to work with, its ability
to work with handwriting (which varies significantly from person to person) might prove to be
too difficult and can be negatively impacting the API’s ability for character recognition. If it can
surpass this limitation however, miscommunication from person to person because of different
handwriting might decline if the writing was passed through this algorithm first.
The API was put to the test against all three forms of “writing” and a robustness
percentage was calculated (how many words was the API able to correctly detect out of the
total number of words). The handwriting should be the hardest to read whereas the webpage
should be the easiest and the scanned should be in the middle. This means the robustness
percentage should fall as the API moves from Webpage to Scanned to Handwriting. Through
this testing, we should be able to determine the efficacy of the GCP’s Machine Learning API for
character recognition and how it can work with actual handwriting.

Link to our Google Spreadsheets: https://docs.google.com/spreadsheets/d/1lHN2bpZval_roapo8f_UD4PWW-C-jWE93kyo7JzVG8Q/edit?usp=sharing
