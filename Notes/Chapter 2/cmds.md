

<p>$ cp file1 file2 ----> file1.contents => file2.contents.</p>
<p>$ cp file1...fileN Dir ----> (file1,fileN) => Dir.</p>
<p>$ mv file1 file2 ---> file1 renamed to file2.</p>
<p>$ mv file1...fileN Dir ----> (file1,fileN) => Dir.</p>
<p>$ rmdir Dir ---> Delete Dir only if Dir.contents = 0.</p>
<p>$ rm -rf Dir ---> Delete Dir.</p>

<h3>Globbing (Wild cards)</h3>

<ul>
  <li>Shell recognizes simple patterns to file and directory names.</li>
  <li>Shell matches arguments containing globs to filenames.</li>
  <li>Shell runs the revised command line.</li>
  <li>The subsitution is called expansion.</li>
</ul>

<h3>Expanding filenames</h3>

<ul>
  <li>text* => all filenames that start with text.</li>
  <li>*text => all filenames that end with text.</li>
  <li>*text* => all filenames that contain text.</li>
</ul>

<h3> ? Glob Character</h3>

<ul>
  <li>?oat => all filenames that have (any char) + (oat)</li>
  <li>foo? =? all filenames that have foo + (any char)</li>
</ul>
  
  
<h2>Intermediate Commands.</h2>

<h3>Grep</h3>

<ul>
  <li>$ grep (expression) (file/input stream) => prints every line in (file/input stream) that contains (expression).</li>
  <li>-i --> case sensitive.</li>
  <li>-v --> invert, or print out each line that doesn't contain expression.</li>
  <li>-E --> egrep, a more powerful version of grep.</li>
  <li>grep understands Regex (regular expression).</li>
</ul>

<h3>Less</h3>

<ul>
  <li>Allows you to see the contents of a file one screen at a time.</li>
  <li>Prevents terminal from overflowing.</li>
  <li>Press spacebar to go forward, and b to go back.</li>
  <li>Press q to quit.</li>
  <li>Type /word to search for a word.</li>
  <li>Type ?word to search backwords for a word.</li>
  <li>When you find a match, press n to continue.</li>
  <li><b>Example:</b> $ grep /etc/passwd/ | less</li>
  <li><b>Note:</b> "|" allows you to send an stdout into an stdin.</li>
</ul>

<h3>Pwd</h3>

<p>Prints the current working directory path.</p>

<h3>Diff</h3>

<ul>
  <li>$ diff file1 file2 ---> shows the difference between file1 and file2.</li>
  <li>use -u to send the output to somewhere else, perfect for programmers.</li>
</ul>

<h3>File</h3>

<ul>
  <li>Used to see the file format of a file.</li>
  <li>$ file filename --> prints the format of filename.</li>
</ul>

<h3>Find and Locate</h3>

<ul>
  <li>$ find dir -name file -print ---> Finds file in dir.</li>
  <li>Locate is based on an index the system builds periodically.</li>
  <li>Locates the file in that index.</li>
  <li>If the file is newer than the index, locate won't find it.</li>
  <li>Locate is faster than find.</li>
</ul>

<h3>Head and Tail</h3>

<ul>
  <li>$ head file1 ---> Prints the first 10 lines of file1.</li>
  <li>$ tail file1 ---> Prints the last 10 lines of file1.</li>
  <li>Use -n option to specify number of lines to be printed, n : number of lines.</li>
</ul>

<h3>Sort</h3>

<ul>
  <li>Sorts the lines in a file based on alphabetic order relative to the first char of the lines.</li>
  <li>Use -n if the first char is a number ---> sorts the lines based on numeric order.</li>
  <li>Use -r to reverse the order.</li>
</ul>

<h3>How to change your password on Shell</h3>

<p>Use the passwd command to change your password on shell. It will ask you for your old password.<br></br>Then it will prompt you two times for your new password.</p>

<h3>Dot files</h3>

<ul>
  <li>Start with ".", example is .ssh.</li>
  <li>use ls -a to ignore dot files.</li>
</ul>

<h3>The Command Path</h3>

<ul>
  <li>PATH is an environment variable that contains the command path.</li>
  <li>A command path is a list of system directories that the shell searches when trying to locate a command.</li>
  <li>$ PATH=$PATH:dir --> Appends dir to command path.</li>
  <li>$ PATH=dir:$PATH --> Appends dir to the start of the list.</li?
</ul>

<h3>Special characters</h3>

![Image of all the special characters.](https://github.com/HypeByte/My-Linux-Notes/blob/master/Assets/Linux%20Special%20Characters.PNG)








