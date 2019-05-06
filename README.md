
put in root cronjob

#
# mins[0-59] hrs[0-23] day-of-month[1-31] month[1-12] weekday[0-6]
#
# sync date/time with time.nist.gov four times a day - move to Azure, no need anymore
#23 3,11,17,21 * * * /usr/local/bin/synctime >/dev/null 2>&1
#

