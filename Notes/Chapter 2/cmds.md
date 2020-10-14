

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





