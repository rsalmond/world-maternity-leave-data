# Maternity Leave Data

Collection of data about maternity leave policy around the world. Includes three fields: country, days of leave, percentage of salary paid.

#Sources:
 * [Wikipedia](https://en.wikipedia.org/wiki/Parental_leave) (current-ish? I dunno it's wikipedia!)
 * [United Nations](http://data.un.org/DocumentData.aspx?id=344) (july 2013)


# Notes:
 * Where possible the WORST case has been used.
   * Bosnia and Herzegovina pay 50%-100%, displayed as 50%.
   * Canada pays 50%-80% depending on income, displayed as 50%.
   * Libya pays 50% for employed women, 100% for *self* employed women, displayed as 50%.
   * Saudia Arabia pays 50%-100%, displayed as 50%.
   * Vietnam offers 4-6 months depending on circumstances, displayed as 4.

 * Where the amount of pay decreases over time the pay has been averaged over the time off.
  * Albania pays 21 weeks at 80% and another 31 at 50%, displayed as 62.1%.
  * Antigua pays 6 weeks at 100% and another 7 at 60%, displayed as 78.4%.
  * Bahamas pays 12 weeks at 100% and another 1 at 66.7, displayed as 97.4%
  * Belgium pays 4 weeks at 82% and another 11 at 75%, displayed as 76.8%.
  * Croatia pays 25 weeks at 100% and another 32 at a flat rate. TODO: something.
  * Grenada pays 8 weeks at 100% and another 5 weeks at 65%, displayed as 86.5
  * Haiti pays 6 weeks at 100% and another 6 unpaid, displayed as 50%.
  * Honduras pays 10 weeks at 100% and another 2 unpaid, displayed as 83.3%.
  * Ireland pyas 26 weeks at 80% and another 16 unpaid, displayed as 49.5%
  * Jamaica pays 8 weeks at 100% and another 4 unpaid, displayed as 66.7%.
  * Malta pays 14 weeks at 100% and another 2 unpaid, displayed as 77.7%.
  * Paraguay pays 9 weeks at 50% and another 3 unpaid, displayed as 37.5%.
  * Rwanda pays 6 weeks at 100% and another 6 at 20%, displayed as 66.5% overall.
  * Sri Lanka pays 12 weeks at 100% and another 12 at 50%, displayed as 75% overall.
  * Swaziland pays 2 weeks at 100% and the remaining 10 weeks are unpaid, displayed as 16.6% overall.
  * Thailand pays 45 days at 100% and another 45 days at 50%, displayed as 83.3% overall.
  * United Kingdom pays 6 weeks at 90%, a flat rate for the next 32 weeks, and the remaining 14 weeks are unpaid. TODO: something

 * For source leave values given in weeks days are computed as (weeks * 7), for those given in months days are computed as (months * 30).
 * For simplicity "days", "calendar days" and "workdays" (included in UN data) are all considered "days".

#Flat Rates:
 * Australia: rather than a percentage of salary it pays the national minimum wage (AUS $672.70 / week) for 18 weeks. (Maybe percentage could be computed against average wages?).
 * Fiji: pays a flat rate for 84 days (TODO: how much?).
 * Kyrgiztan: 7x minimum wage (TODO: how much?)
 * Seychelles: flat rate for 12 weeks, unpaid remainder.

#Fine Print:
 * Libya: 100% for self employed women, 50% for everyone else.
 * New Zealand: 100% or NZ516.85 / week, whichever is lower.
 * Qatar: only available for civil servants.

#Upper Limits:
 * Belgium: pays 76.8% (averaged) up to a ceiling.
 * Candada: pays between 55-80% depending on income up to a max of CAD $524 / week.
 * Chile: 100% up to a ceiling.
 * Ireland: pays 49.5% (averaged) up to a celiing.
 * Monaco: 90% up to a ceiling.
 * Namibia: 100% up to a ceiling.
 * Netherlands: 100% up to a ceiling.
 * Russia: 100% up to a ceiling.
 * Slovenia: 100% up to a ceiling.
 * Spain: 100% up to a ceiling.
 * Sweden: 80% up to a ceiling.
 * Switzerland: 80% up to a ceiling
 * Thailand: last 45 days have a ceiling of 7500 baht / month.

#Disclaimer:
I put in a fair amount of work to make this as accurate as possible but I did this on a lark, I'm sure it's not perfect. If you find a mistake please let me know!
