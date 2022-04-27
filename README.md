# gcal-manual
A manual for 'gcal', the gnu calendar program
NOTE: This is a work in progress. I currently understand about 10% from what is happening with the gcal interface !!!!


gcal can display a surprising number of calendar variations, including such as european, chinese and muslim. You can additionally display holidays in your region, or other special events, such as sun rise or moon phase.

The standard GNU manual for gcal might be hard to understand fully, therefore I have written this summary to help you get up to speed with the abundance of options.

gcal will take options (preceded by the ususal "-" or "--") on the commandline, but also "commands". The commands constiture a sort of database-query on all possible calendars and special days. You may find it usefull, but I could not imagine applications for it. This "query language" is cerntainly non-standard and quiet complex as a result. 


# Standard Calendar display
"gcal" will display a fairly standard calendar layout, with weekdays per column

"gcal -i" will display an "inverted" standard calendar display, with weekdays per row.

"gcal 2019" will display the years calendar.

"gcal 5" will display the months (in this case May) calendar. You may also combine to "gcal 2012 9", eg september 2012

"gcal %yyyyymm" will display the calendar for the month "mm" of the year "yyyy" (you may also leave out yyyy). In general the "%" option is used to specify some other date than the default current systemdate.

Confusingly, you can also specify months with another command, namely the "." command. this will display three months, with the current month in the middle. The commands ".+" and ".-" will display three months with the current month as the first, respectively the last of the three.

Similaly the ".." command will display regular quarters of a year.

You can give a list of "commands", by seperating with comma's.

You can give a range of "commands", by seperating with a dash "-".

Options (and commands) will also be taken from the ENVIRONMENT variable "GCAL". They will be superseeded by the command line. 
