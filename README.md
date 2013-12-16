# IRC Logparse

For text based IRC logs which utilize the following format:

    [HH:MM] <USER> MESSAGE

This script will count how many times a user has spoken and a running total of the users who were talking.

# Installation

Place `irc-logparse` in your path somewhere

# Usage

irc-logparse has the following options:

    irc-logparse -s <server> -y <year> -m <month> -d <day> <room>

 - `-s <server>` IRC Log server (irclogs.ubuntu.com)
 - `-y <year>` Year of the log (YYYY, current year)
 - `-m <month>` Month of the log (MM, current month)
 - `-d <day>` Day of the log (DD, current day)
 - `<room>` Room to parse

# Examples

    irc-logparse -m 11 -d 15 juju

Get the running total from the first of November to the 15th from the #juju room
