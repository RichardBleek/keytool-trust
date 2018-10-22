# keytool-trust

Tool to install SSL certificates in JVM keystores
This version is edited to run on Windows machines using a bash emulator

## How to use?
./keytool-trust server [port]

If port is not specified it will assume 443.

You can use it to trust certificates from:

* HTTPS 443
* LDAPD 636 / 3269
* MAIL 993 / 995
