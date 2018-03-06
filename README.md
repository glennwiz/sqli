# sqli
![bobby](http://daddytypes.com/archive/xkcd_bobby_tables.jpg)

# -----------------------------

var textboxvalue = textbox.value.ToString();
Select id from user where name = '%textboxvalue%';

# -----------------------------

var textboxvalue = "; DROP DATABASE Prodbase --";
Select id from user where name = '; DROP DATABASE Prodbase --';

-----------------------------
[sqlmap](http://sqlmap.org/)

[OwaspTop10](https://www.owasp.org/index.php/Main_Page)