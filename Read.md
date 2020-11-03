To uplead two datasets bothe were more than 1 GB, i have pushed it via github via LFS (large file system) 
Commands for that 

cd "any directory" 
git init
git clone (github repo url) 
cd "cloned directory) 
git lfs install
git lfs track "*.mp4" ( any type of file)
git add .gitattributes
git add test.mp4
git commit -m "Upload video"
$ git push origin master
if error comes see this link ( https://github.blog/2017-06-27-git-lfs-2-2-0-released/) 
git lfs migrate info
git lfs migrate import --include="*.psd"
git push origin
