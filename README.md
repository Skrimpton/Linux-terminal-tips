Simple terminal tricks

` 
if [ -d "$PWD" ];then
  echo "Yeah it is"
else
  echo "Hmmm... It should be"
fi 
`

**Can also be written as:

`
[ -d "$PWD" ] && {
echo "ofc"
} || {
echo "lol wut"
}
`
*In KDE's konsole running zsh ALT+ENTER adds a newline in the command prompt, where this version is easier to type and read from history than long lines using ;

