
## Version 10.3

我們固定選擇版本 10.3 是為了教學方便減少因為版本帶來的錯誤，大家自己在玩的時候可以用最新版 **latest** 。


```bash
# for get sagemath docker image
docker pull sagemath/sagemath:10.3
# run 
docker run -it sagemath/sagemath:10.3
# run on jupyter
docker run -p 8888:8888 sagemath/sagemath:10.3 sage-jupyter
# stop container
docker stop ${container ID}
# check container ID
docker ps
```

