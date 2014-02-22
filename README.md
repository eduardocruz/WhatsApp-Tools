# WhatsApp Tools

**Contact with me: me [at] mgp25.com or @_mgp25**

----------
### Instrucciones y líneas básicas 

Logging in / Iniciando sesión

```php
 $username = ''; // Number with country code
 $password = ''; // Password obtained with WART or WhatsAPI
 $identity = ''; // $identity is no longer necessary
 $debug = false; // You can set true, for more details

 $nickname = "WA Tools"; // This is the username (or nickname) displayed by WhatsApp clients.
  

$w = new WhatsProt($username, $identity, $nickname, $debug);
$w->connect();

// Now loginWithPassword function sends Nickname and (Available) Presence
$w->loginWithPassword($password);
```

