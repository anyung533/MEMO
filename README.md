#SHELL

视频连接：www.youtube.com

shebang

cd patch

git add .

DATE=$(date)

git commit -m "change made on $DATE"

git push

osacript -e "display notification 'push to remote' with tile "SUCCESS"