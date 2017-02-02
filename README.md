# Mailer

* Date:    August 13, 2014
* Author:  Jaime A. Rodriguez <hi.i.am.jaime@gmail.com>
* Version: 1.8
* License: http://opensource.org/licenses/MIT

Simplifies sending emails by automatically verifying email addresses and fetching HTML.

## Usage

~~~ php
	$m = new \Module\Mailer\Message();
	$m->addTo("test@test.com");
	$m->addFrom("from.me@test.com");
	$m->addSubject("This is a test, don't panic.");
	$m->fetchHTML("http://test.com/template.php");
	$m->send();
~~~

## Changelog
### Version 1.9 
 * Added -f parameter to "from" address 
 
### Version 1.8
 * Added namespacing

### Version 1.6
 * Fixed bug with BCC and CC
