#README.md
# Initialize Environment
in terminal:
.git --version
# Common Used Instrution
.git status
.git log --oneline
# Track File and Folder
create a new EADME.md file, ctrl + s
.git add [full file name]
.git add *.file_sub_name
.git add .
.git commit -m 'message'
# others instruction of modify file
.git reset --soft HEAD~ #回到上一動
.git reset --hard [version.number]
.git diff [version.number] -- [filename]
.git checkout [version.number] -- [filname]