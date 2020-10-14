

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

