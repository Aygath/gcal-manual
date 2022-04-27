# gcal-manual
A manual for 'gcal', the gnu calendar program

gcal can display a surprising number of calendar variations, including such as european, chinese and muslim. You can additionally display holidays in your region, or other special events, such as sun rise or moon phase.

The standard GNU manual for gcal might be hard to understand fully, therefore I have written this summary to help you get up to speed with the abundance of options.

gcal will take options (preceded by the ususal "-" or "--") on the commandline, but also plain "commands". 

# Standard Calendar display
"gcal" will display a fairly standard calendar layout, with weekdays per column

"gcal -i" will display an "inverted" standard calendar display, with weekdays per row.

"gcal %yyyyymm" will display the calendar for the month "mm" of the year "yyyy" (you may also leave out yyyy). In general the "%" option is used to specify some other date than the default, which is the current systemdate.

Confusingly, you can also specify 

There exist options to display multiple months. Eg "gcal %yyyy" will display all months of the year.

