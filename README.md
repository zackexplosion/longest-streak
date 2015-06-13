# longest-streak

Try to figure out how long is the longest streak, on github

# the code
``` bash
for i in {365..3650}
do
date=`date -v +"$i"d +"%Y/%m/%d"`
echo $date >> message.txt 

git add . 
git commit --date="$date" -m "$date"

done
```
