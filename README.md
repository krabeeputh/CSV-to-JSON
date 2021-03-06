# CSV-to-JSON
Cvs2Json, a Python class to convert text or CSV (Comma Separated Values) to JSON (JavaScript Object Notation) format for Django model
<h3>Introduction</H3>
<p>
  This is my first program. It is a class module to help you to convert text or CSV to JSON format for <a href="https://docs.djangoproject.com/en/3.1/topics/db/models/">Django model</a> which need three properties: <b>“pk”</b>, <b>“model”</b> and <b>“fields”</b>. See <a href="https://docs.djangoproject.com/en/3.1/topics/serialization/#serialization-formats-json">serialization formats</a> from Djgno more information.
</p>
<p>
  Instead of using <code>strip()</code> and <code>split()</code> functions as the tutorials from https://www.geeksforgeeks.org/convert-text-file-to-json-in-python/ and https://github.com/jcamier/csv-json-django/blob/master/convert_csv_to_json.py. I use Python's built-in <a href="https://docs.python.org/3/library/csv.html">csv library</a>. It is more easier, convenient and powerful. It was born to to read and write tabular data in CSV format which was generated by Microsoft Excel.
</p>
<p>
  I developed this program to support Thai language with utf8 encoding (UNICODE) so I hope it will support any language too.
</p>


<h3>How to use it?</h3>
<p>
  1. Import module<br>
  2. Config some variables
</p>
<ul>
  <li>The CSV file to be converted</li>
  <li>The JSON output file</li>
  <li>App and Model name</li>
  <li>List of fields in your model</li>
</ul>
<p>
  3. Crate object to use<br>
  see more detail in file test.py
</p>

<h3>Input & Output</h3>
<p> I have more 2 files</p>
<ul>
  <li>countries.csv, It's a source file to be converted to JSON format. You can use it for testing the program.</li>
  <li>countries.json, This file auto generate from class. It's my JSON output file. You can run my program to get the same output format</li>
</ul>
