# Small-Projects

A collection of small projects done to practice

## Simple Guessing Game
A simple game that has the player set the floor and the ceiling in the range of their game, then tries to guess the number

## Mad Libs Game

A simple game that uses one of 5 monologues from well known movies, and has the player fill out a mad-libs version of it. Uses PyDictionary to check if a word is a verb or adjective https://pypi.org/project/PyDictionary/#description

## Hang Man Game

A simple game that draws from a library of random words and makes you guess each letter to guess the word. Uses random-word dictionary to get the words. https://github.com/vaibhavsingh97/random-word/

## World Indicators Dataset

A simple data visualization exercise in pandas using a kaggle dataset with the same name. Compares availible data of GINI index with Female Leaders, then compares fertility rate with the amount of arable land. The former had no notable correlation, the latter had correlation depending on which area the comparison was done and income level.

## Hex To Base64

A number of functions run together to convert a hexadecimal to base64.
>Hexadecimal to Binary
  - Based on a dictionary, for each digit or letter in a hex string, put its corresponding 4 digit binary string then return the string
  
>Binary to Base64 Numbers
  - A basic binary to decimal converter that chunks a binary string into groups of 6 and transforms it into a decimal
  
>Base64 Number Reader
  - Returns corresponding Base64 values in "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/" from a decimal
  
## NYC Data Set Analysis
A simple analysis of data analytics of crime in NYC using matplotlib for static data and bokeh for interactive data. 
- All crimes have steadily lowered since 1990, however Rape sharply increased between 2014 and 2015, increasing by around 1200 cases, or around a 100% increase, and has been holding a constant rate, if not slightly increasing since then. This could be due to the strong support for sexual abuse victims in recent years, normalizing the act of reporting it and encouraging having these victims come forward instead of the behavior of hiding it. The change in social landscape in the current and coming years could either get stronger and potentially increase these claims further, or die out and decrease the number, so I expect rape claims to be a volatile number.
- There is a strong negative correlation of about -.9 between Average Salary and Cases of Larceny. Cases of larceny historically have been the largest percentage of crime in NYC, and though the total number of larceny cases has decreased, the percent of cases compared to total crimes has increased, from 37.9% in the 1990s, to 63.1% in 2017. This is due to other major crimes, such as Motor Vehicle Theft and Burglary decreasing at a faster rate. However, it makes sense that the higher the average salary is in a city, the less likely theft would be necessary to occur. This doesn't take into account other factors such as industry specific average salaries or pay gap inequality.
- There is a surprisingly weak correlation between DWI arrests and Drug arrests between 2007 and 2017, with DWI Arrests being a only 0.0015 correlation and Drug Related Arrests being a -0.2826 correlation. I am unable to discern whether the police force has too many officers or not enough, as the data itself does not focus on specific departments or how many arrests each department makes towards what crime.
>Data Used:

  https://data.ny.gov/Economic-Development/Quarterly-Census-of-Employment-and-Wages-Annual-Da/shc7-xcbw
  
  https://data.ny.gov/Public-Safety/Index-Crimes-by-County-and-Agency-Beginning-1990/ca8h-8gjq
  
  https://data.ny.gov/Public-Safety/Adult-Arrests-by-County-Beginning-1970/rikd-mt35
  
  https://data.ny.gov/Public-Safety/Law-Enforcement-Personnel-by-Agency-Beginning-2007/khn9-hhpq

## Vigenere

A simple program that can encode or decode a message. It takes n keys, finds the least common multiple of the length of the keys, sets each key to the length of the least common multiple, then uses each of its key to create one master key. It then uses the Vigenere method to encode your message using the master key. Essentially, the reason it does this is that assuming the user uses keys of different lengths, it can becomes something close to a single use key that is as long as the message, which makes the encoded message extremely hard to break. It also encodes most ASCII characters.
