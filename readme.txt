# contact plugin
# Plugin for B3 (www.bigbrotherbot.com)
# www.ptitbigorneau.fr

need smtp server

contact plugin (v1.4-lt) for B3

Installation:

1. Place the contact.py in your ../b3/extplugins and the 
contact.ini in your ../b3/extplugins/conf folders.

2. Open contact.ini

modify e_mail address for send message
modify e_mail address for receive message
modify server name
modify smtp server name  (localhost or smtp.exemple.com)
for smtp.gmail.com 
  modify gmailusername 
  modify gmailpwd  

3. Open your B3.xml file (default in b3/conf) and add the next line in the
<plugins> section of the file:

<plugin name="contact" config="@b3/extplugins/conf/contact.ini"/>

4. Run the contact SQL script contact.sql on your B3 database