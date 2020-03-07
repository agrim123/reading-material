# Web Security

## Vulnerabilities

- Cross-site Scripting (XSS)
- Open Redirects
- SQL Injection
- Remote Code Execution
- Heartbleed (vulnerability in some implementations of OpenSSL)

### Open Redirects

- [CWE-601: URL Redirection to Untrusted Site ('Open Redirect')](http://cwe.mitre.org/data/definitions/601.html)
- [Open redirect URLs: Is your site being abused?](https://webmasters.googleblog.com/2009/01/open-redirect-urls-is-your-site-being.html)


## Cross-site Scripting (XSS)

XSS is a web application vulnerability which lets attacker run his own scripts (client side) on web pages.  
It can be dangerous as attacker can steal cookies, credentials, [phishing](https://en.wikipedia.org/wiki/Phishing) and many sensitive details by successfully exploiting XSS vulnerability.  
In most cases, an input form can be used by attacker to inject malicious code.

Suppose we have a search route 
```
https://my_domain.com/search?q=some_random_query
```
And we get results.

But if the search input is not properly passed then by doing something like
```
https://my_domain.com/search?q=<script>alert('You are hacked!');</script>
```
Will display an alert box upon succesful retrival of search results.

Morever an attacker can also inject an image instead of an alert box.
```
https://my_domain.com/search?q=<img src="link_to_a_taunting_image" />
```
XSS is not limited to the above examples.

It can be used to exploit a forum for example (if inputs are not properly passed). An attacker will post a malicious code in his comment and that code will run whenever any client visits that page.

### HTTP Strict Transport Security

HTTP Strict Transport Security is a web security policy mechanism which helps to protect websites against protocol downgrade attacks and cookie hijacking. It allows web servers to declare that web browsers should only interact with it using secure HTTPS connections, and never via the insecure HTTP protocol.
