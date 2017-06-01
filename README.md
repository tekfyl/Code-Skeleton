# Code-Skeleton
## Directly add basic required code skeleton in you c and cpp files.
### Just copy these cpp.skel and c.skel files here -> ~/vim/
### Also add these lines in your .vimrc file
        au BufNewFile *.cpp 0r ~/.vim/cpp.skel | let IndentStyle = "cpp"
        au BufNewFile *.c 0r ~/.vim/c.skel | let IndentStyle = "c"
