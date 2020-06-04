git log --pretty=format:'"%ad","%an"' --after="2018-12-31" --until="2020-01-01" >namelog.csv


git log --pretty=format:'"%aD","%an","%s","%h",' --shortstat --no-merges | paste - - - > detaillog.csv
