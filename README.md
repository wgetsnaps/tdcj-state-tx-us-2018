# Snapshot of Texas Death Penalty site

You can view the mirrored version by visiting this URL:

https://wgetsnaps.github.io/tdcj-state-tx-us-2018/death_row/

This repository is a mirror of the following site:

|        Key         |                 Value                  |
|--------------------|----------------------------------------|
| Site title         | Death Row Information                  |
| Original publisher | Texas Dept. of Criminal Justice        |
| URL                | http://www.tdcj.state.tx.us/death_row/ |
| Mirrored at        | 2018-01-31 19:43 PM                    |


You can find a 2016 snapshot at this repo:

https://github.com/wgetsnaps/tdcj-state-tx-us--death_row






# How to wget

This is the __wget__ command(s) I used:

~~~sh
wget --mirror \
     --page-requisites \
     --convert-links \
     --no-host-directories \
     --adjust-extension \
     --no-parent \
     --output-file /dev/stdout \
     http://www.tdcj.state.tx.us/death_row/ \
     | tee ./wget.log
~~~
