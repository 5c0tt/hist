08.08.2015 — 07:40:10 PM -0700  
Scott Haneda [@scotthaneda](https://twitter.com/scotthaneda)

# Hist — A quick shell history parser

## A huge one line mess, feel free to improve.  
( Sample output… )

    @foonty hist $hist
         1	122  24.4%  l
         2	102  20.4%  git
         3	71   14.2%  cd
         4	20   4%     open
         5	20   4%     mate
         6	15   3%     ls
         7	12   2.4%   dt
         8	12   2.4%   curl
         9	11   2.2%   rm
        10	10   2%     pwd


### Collects values out of `history` command and sums up stats on the top ten used with counts.