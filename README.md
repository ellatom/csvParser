<h1>csvParser</h1>
<div>CSV file is a file that represents a table structure in a text format.</div>

<div>For example,</div>
<div>Name, Age, Country</div>
<div>Omri, 35, Israel </div>

<div>First line will contain the headers separated by commas , the next lines will contain the data itself, separated by commas.
<div>Write a csv parser that deserializes a CSV file into a typed list of js objects. 
<div>It should parse each row into an object, where each columns is corresponds to a property. 
<div>Strings should be represented as string, numbers as numbers etc.
<div> [{name:”omri”,age:35,country:”israel”},..]
