grep -rnw . -e '-lsocket' 
find ./ -type f -exec sed -i 's/-lsocket//' {} \;
[StackOverflow](https://stackoverflow.com/questions/11392478/how-to-replace-a-string-in-multiple-files-in-linux-command-line)
Kaspar L. Palgi's answer