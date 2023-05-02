Download Link: https://assignmentchef.com/product/solved-comp9044-test-4-create-intergers-file
<br>
Write a Shell program, create_integers_file.sh which takes 3 arguments.

The first &amp; second arguments will specify a range of integers.

The third argument will specify a filename.

Your program should create a file of this name containing the specified integers.

For example:

Your answer must be Shell. You can not use other languages such as Perl, Python or C.

You are not permitted to use the Linux program seq.

No error checking is necessary.

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest shell_create_integers_file</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test04_shell_create_integers_file create_integers_file.sh</strong>

Write a Perl program, create_integers_file.pl which takes 3 arguments.

The first &amp; second arguments will specify a range of integers.

The third argument will specify a filename.

Your program should create a file of this name containing the specified integers.

For example:

$ <strong>./create_integers_file.pl 40 42 fortytwo.txt</strong>

$ <strong>cat fortytwo.txt</strong>

40

41

42

$ <strong>./create_integers_file.pl 1 5 a.txt</strong>

$ <strong>cat a.txt</strong>

1

2

3

4

5

$ <strong>./create_integers_file.pl 1 1000  1000.txt</strong>

$ <strong>wc 1000.txt</strong>

1000 1000 3893 1000.txt

Your answer must be Perl only. You can not use other languages such as Shell, Python or C.

You may not run external programs, e.g. via system or backquotes.

No error checking is necessary.

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest perl_create_integers_file</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test04_perl_create_integers_file create_integers_file.pl</strong>

It will be given two arguments <em>n</em> and the file name.

Your program should print nothing if the file does not have an <em>n</em>-th line You can assume <em>n</em> is a positive (non-zero) integer.

You should not assume anything about the lines in the file.

Your answer must be Perl only. You can not use other languages such as Shell, Python or C.

You may not run external programs, e.g. via system or backquotes.

No error checking is necessary.

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest nth_line</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test04_nth_line nth_line.pl</strong>