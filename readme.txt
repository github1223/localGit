readme.txt created in 26 Jan. 2016

/*install Git for windows */ 

1. download the Git for windows 32bit version.
 Git-2.11.0.32-bit.exe
https://github-cloud.s3.amazonaws.com/releases/23216272/31f4597e-da58-11e6-8a7d-ca33d8159312.exe?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAISTNZFOVBIJMK3TQ%2F20170126%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20170126T121730Z&X-Amz-Expires=300&X-Amz-Signature=6a6dde3447b61a133b84cbf3c7474546934a8f3d4c0779e80afe07c20d4318a4&X-Amz-SignedHeaders=host&actor_id=0&response-content-disposition=attachment%3B%20filename%3DGit-2.11.0.3-32-bit.exe&response-content-type=application%2Foctet-stream

2. create new directory in disk
c:/Git

3. execute Setup file.

4. create sub-directory /localGit

5. cd localGit

6. 初始化Git本地仓库
   git init

7. Notepad++编辑readme.txt文件，并保存到/localGit目录

8. 追加文件到本地仓库
    git add  readme.txt
   
9. 提交Git备案
    git commit -m "wrote a readme file"   

10. 继续编辑readme.txt

11. 检查文件是否有修改
     git status

12. 确认文件中何处有修改
     git diff readme.txt

13. 追加修改文件readme.txt
     git add readme.txt

14. 提交Git备案
     git commit -m "update readme file"
	 