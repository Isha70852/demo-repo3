# Demo 2
將本機的檔案push到github

1.新增資料夾
2.新增README.md檔案
3.輸入 git init -->此時會建立.git資料夾
4.git status確認
5.git add .
6.git commit -m "Add README.md" -m "description"
7.到github上新增repo，保持全部空白，將ssh複製下來
8.git remote add origin 複製的ssh
9.git remote -v --用來確認和誰連接
10.git push -u origin master --加上-u之後以後就可以只打git push