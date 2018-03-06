# sqli
![bobby](http://daddytypes.com/archive/xkcd_bobby_tables.jpg)

# -----------------------------

var textboxvalue = textbox.value.ToString();

var query = "Select id from user where name = '" + textboxvalue + "' AND name != 'Admin'";

# -----------------------------

var textboxvalue = "; DROP DATABASE Prodbase --";

## Query
Select id from user where name = '; DROP DATABASE Prodbase --' AND name != 'Admin'";

# -----------------------------

uname = tbxusername.value;  
passwd = tbxpassword.value;

sql = “SELECT id FROM users WHERE username=’” + uname + “’ AND password=’” + passwd + “’”

uname = 'test'
passwd = "' OR 1=1"

## Query
SELECT id FROM users WHERE username=’test’ AND password='' OR 1=1

# -----------------------------


# Best practices for preventing SQL injection attacks
Use stored procedures  
Use dynamic SQL only when you can't avoid it - vist du må bruk feks REPLACE på type singelquotes o.l som kan komme inn fra user.  
Use the principle of least access when granting database access  
Use testing and monitoring to guard against SQL injection  
Protecting against SQL injection attacks  

https://statoil.service-now.com/kb_view.do?sysparm_article=KB0040762&sysparm_stack=&sysparm_view=

[sqlmap](http://sqlmap.org/)
[OwaspTop10](https://www.owasp.org/index.php/Main_Page)
