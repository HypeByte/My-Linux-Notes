

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

<p>$ grep (expression) (file/input stream) => prints every line in (file/input stream) that contains (expression).</p>





