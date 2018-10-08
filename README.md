# Unix-and-Shell-Programming-16CS33-Assignment

<h3>znew:</h3>
Znew recompresses files from .Z (compress) format to .gz (gzip) format. If you want to recompress a file already in gzip format, rename the file to force a .Z extension then apply znew. 
<br><br>
<u>Options:</u>
<ul>
<li>-f  :  Force recompression from .Z to .gz format even if a .gz file already exists.</li>
<li>-t  :  Tests the new files before deleting originals. </li>
</ul>
<br><br>
<u>Examples:</u>
<ol>
<li>
znew -f
<br>
<img src="https://raw.githubusercontent.com/malhark13/Unix-and-Shell-Programming-16CS33-Assignment/master/znew-f.png"/><br>
<b>Explanation: </b>Converts *.Z file to *.gz file. Here it converts test.Z to test.gz
</li>
  <br>
<li>
znew -t
<br>
<img src="https://raw.githubusercontent.com/malhark13/Unix-and-Shell-Programming-16CS33-Assignment/master/znew-t.png"/><br>
<b>Explanation: </b>Test integrity of the (test.gz) gzipped file	before deleting	the original file.  If the integrity check fails, the original (test.Z) `.Z' file is not removed.
</li>
</ol>
