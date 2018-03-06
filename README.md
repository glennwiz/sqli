# sqli
![bobby](http://daddytypes.com/archive/xkcd_bobby_tables.jpg)

# -----------------------------

var textboxvalue = textbox.value.ToString();

var query = "Select id from user where name = '" + textboxvalue + "' AND name != 'Admin'";

# -----------------------------

var textboxvalue = "; DROP DATABASE Prodbase --";

# Query
Select id from user where name = '; DROP DATABASE Prodbase --' AND name != 'Admin'";

# -----------------------------

uname = tbxusername.value;
passwd = tbxpassword.value;

sql = “SELECT id FROM users WHERE username=’” + uname + “’ AND password=’” + passwd + “’”

passwd = "' OR 1=1"

SELECT id FROM users WHERE username=’username’ AND password='' OR 1=1’

# -----------------------------

[sqlmap](http://sqlmap.org/)

[OwaspTop10](https://www.owasp.org/index.php/Main_Page)
