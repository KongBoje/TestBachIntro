# TestBachIntro

Hello World!

## git tutorial
https://try.github.io/levels/1/challenges/1

https://community.linuxmint.com/tutorial/view/100  -Commands tutorial


## Commands
git add .

git commit -m "text"

git pull

git push


## Creating files

Touch <name>

"program name" 'filename'

(stdout) > Filename

echo "some text" > aNewFile

cat << EOF > data/my_data.csv  -multi creation of a file.

## Writing a bash script

Start a script with this:

#!/bin/bash


## More commands

mkdir "name"  -creates folder.

touch "filename"  -creates a file.

echo 'hello world' > "filename"  -deletes what's already in the file and instead writes "Hello World" ">" = is a redirect and overrides.  ticks (') are used if there are spaces.  >> = appends to current words

echo 'hello world' | tee "filename"  -Sends the output to both a file and the terminal, "|" = a pipe and the ' | ' sends the output of dmesg to tee.


## Docker tutorial

http://tiny.cc/py3dny  -Teaches you what a container is

https://www.docker.com/community-edition  -Download and install Docker here.

docker run -it debian  -try this, You get redirected into shells debian.

Read this article about containers: http://tiny.cc/4qflqy.

container = wrapper.

docker ps -a = a is a new instance, Hej() f.eks.

docker run -it alpine:latest /bin/sh  -alpine is the same as debian but smaller and provides with the latest version. Isolated containers.

docker rm "name"  -removes a file

sudo docker run -it debian  -Directs you into the debian container where 
you can use commands like ls, cd etc. name on that container = 
"root@'name'"

vagrant@vagrant:~$ sudo docker ps -a  -gives me a list of the container 
ID's

github/soft mappe = competition, echo istedet for ehco
