
// this is properly formated CSV
git log --pretty=format:"%ad%x2C%an%x2C%x22%s%x22%x2C%h" --after="2017-12-31" --until="2019-01-01" --no-merges > detaillog.csv

