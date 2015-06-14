# Longest-streak

Try to figure out the longest streak on github

# The code
``` bash
for i in {365..3650}
do
date=`date -v +"$i"d +"%Y/%m/%d"`
echo $date >> message.txt 

git add . 
git commit --date="$date" -m "$date"

done
```

# Writing jobs on public contributions

![Imgur](http://i.imgur.com/hXcoza7.jpg)
