# git使用

	SSH_URL :https://github.com/newbeedaly/hello.git

## 1. create a new repository on the command line

	echo "# hello" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/newbeedaly/hello.git
	git push -u origin master

## 2. push an existing repository from the command line
	 
	git clone https://github.com/newbeedaly/hello.git
	# git remote add origin https://github.com/newbeedaly/hello.git
	git add file.md
	git commit -m "file commit"
	git push -u origin master