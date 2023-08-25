# Cross-site Scripting (XSS)


Cross-Site Scripting (XSS) is a type of security vulnerability commonly found in web applications. It occurs when a web application allows malicious code to be injected into a webpage - It is usually in javascript - that is then viewed by other users. This can happen when the application doesn't properly validate or sanitize user-generated input before displaying it on a page.

# How does XSS work?
Cross-site scripting works by manipulating a vulnerable web site so that it returns malicious JavaScript to users. When the malicious code executes inside a victim's browser, the attacker can fully compromise their interaction with the application.

# XSS Types

1. **Stored XSS**: In this type of attack, the malicious script is stored on the server and is served to users when they visit a particular page. This often happens when user input is not properly sanitized and is directly inserted into a database or a file that is later read by other users.

2. **Reflected XSS**: Here, the malicious script is embedded in a URL and is reflected off a web server onto a webpage. This can occur when a user clicks on a specially crafted link and the script is executed in the context of their session.

3. **DOM-based XSS**: This is a type of XSS that occurs on the client side, within the Document Object Model (DOM) of a web page. The attack takes advantage of the way the page's scripting code interacts with the DOM, allowing the malicious script to be executed within the user's browser.

<br/>

> **Note**
You can read more about the vulnerability at the [Portwigger Website](https://portswigger.net/web-security/cross-site-scripting)















