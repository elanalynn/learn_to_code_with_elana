# Command Line Interface (CLI)

## By the end of this lesson, you should be able to...

- Explore the Command Line Interface (CLI)
- Install tools and set up accounts
- Explain Git and GitHub?

## Command Line Interface (CLI)

Some UNIX commands...

```bash
ls (list)
ls -la (list details and hidden files)
pwd (print working directory)
cd (change directory)
touch (create a file)
mkdir (create a directory)
cat (output the contents of a file)
echo (output whatever you enter afterword)
tree (lists files and directories recursively)
mv (move a file and change names)
cp (copy a file)
rm (remove a file)
rm -rf (remove a directory recursively - be cautious with this!)
grep (search for a pattern in text)

.. (up a directory)
. (current directory)

man (manual)

code . (open this directory in VSC)
open <filename> (open specified file with its default application)
```

- You can redirect and pipe outputs of command into another file or command

```bash
# REDIRECT with an ">"
# Replace contents of hello.txt or if hello.txt doesn't exist, creates it with the text hello
echo hello > hello.txt

# Append hello to the end of hello.txt - file must already exist
echo hello >> hello.txt

# PIPE with a "|"
# Read the contents of hello.txt and search for the pattern "hello"
cat hello.txt | grep "hello"
```

## Check for Understanding
