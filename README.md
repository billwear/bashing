# bashing
what's here so far:

1. a few that avoid the hassle of giving date(1) a format string while doing r! within vi:
 - epoch - pulls in the unix epoch from date(1) ("+%s")
 - julian - pulls in julian day from date(1) ("+%j")
 - miltime - pulls in current time formatted as military time, hhmm
 - week - pulls in the week number from date(1) ("+%U")
 - when - pulls in the unique datestring yyyymmdd from date(1) ("+%Y%m%d")
 
2. next, a script that semi-converts calendar(1) entries to todo.txt; UAYOR.

3. a couple related to the autofocus method of structured procrastination:
 - macro - backs up autofocus files and pulls out items that aren't asleep ("ZZZ")
 - wideangle - backs up autofocus files and wakes up all sleeping ("ZZZ") items
 