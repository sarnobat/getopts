## Verdict
2022-08 `getopt` in Bourne Shell works nicely so far. It allows BSD single arg grouping, mixing options and non-option parameters, and long options. I've read it's not good with whitespace so getopts is better.

getopts
=======

Using getOpts in java.

Never attempted, I think I used commons-CLI because its API was more natural to Java programmers.


## getopt Bourne Shell

See youtube_download.sh

getopt turned out to be more intuitive thain it looked at first. Sticking to getopt and Bourne Shell allowed me to see its original workings. Later I might find limitations and start using getopts, but I vaguely remember 10 years ago there was a problem with getopts.

getopts is a builtin, while getopt is a separate program. So far I like that separation.
