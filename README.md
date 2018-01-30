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

