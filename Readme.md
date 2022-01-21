## Documentation


$ mvn archetype:generate
version: 1.4 groudId: com.capstone
artifactId: com.capstone

git remote add origin https://github.com/easyasf/BankingMicroservice
touch my_file1.txt
git add .
git commit "my_file1.txt is modified by dev1"
git commit -m "my_file1.txt is modified by dev1"
cat my_file1.txt
git checkout dev2
cat 1.java
cat my_file1.txt
git commit -m "1.java file is modified by dev2"
git add .
git commit -m "my_file1.txt file is modified by dev2"
cat my_file1.txt
git checkout Main
git merge dev1
cat 1.java
cat my_file1.txt
git merge dev2
git mergetool
cat my_file1.txt
git status
git add .
cat my_file1.txt
git status
touch Readme.md
vi Readme.md
git log --oneline
vi Readme.md
git add .
git commit -m "Readme.md file is added"
git push origin Main
git log --oneline
vi Readme.md

<ul>	
	<li>c55c102 (HEAD -> Main, origin/Main) Readme.md file is added</li>
	<li>880a246 (HEAD -> Main) my_file1 merged</li>
	<li>9d1c6d0 (dev2) my_file1.txt file is modified by dev2</li>
	<li>3ed9364 (dev1) my_file1.txt is modified by dev1</li>
	<li>62964fc (origin/dev2, origin/dev1, origin/Main) Files is added</li>
</ul>
