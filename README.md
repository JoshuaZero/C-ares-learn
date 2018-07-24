# C-ares-learn

 CCLD     libcares.la
./libtool: eval: line 6447: unexpected EOF while looking for matching `''
./libtool: eval: line 6448: syntax error: unexpected end of file
make[2]: *** [libcares.la] Error 2

解决办法：
eval: line 6447: unexpected EOF while looking for matching `”’

eval sys_lib_dlsearch_path=\”$sys_lib_dlsearch_path_spec\”

在第一个斜线前加两个竖斜杠即可解决该问题，如下：

eval sys_lib_dlsearch_path=||\”$sys_lib_dlsearch_path_spec\”
