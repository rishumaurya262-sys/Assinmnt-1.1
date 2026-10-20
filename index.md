# Assignment 1.1 — How a Website Works

**Objective:** To understand how a website opens in a web browser after typing a URL.

**Answer:**

When a user types a URL (Uniform Resource Locator) into a web browser such as Google Chrome, the browser acts as a client and sends a request to the web server over the internet. First, DNS (Domain Name System) translates the domain name into an IP address so that the server can be located. The browser then sends an HTTP (Hypertext Transfer Protocol) or HTTPS (Hypertext Transfer Protocol Secure) request to the server. HTTP is used to transfer data between a browser and a server, while HTTPS provides an encrypted and more secure connection. The server processes the request and may retrieve information from a database if required. It then sends an HTTP response containing the requested resources, such as HTML, CSS, JavaScript, and images. The browser interprets these resources and displays the website on the screen. This process is called the **request-response cycle**. A static website displays mostly fixed content that  changes only when its files are updated, whereas a dynamic website can generate or change content based on user input, database information, or other conditions. We can inspect these requests and responses using Chrome DevTools by opening the **Network** tab, reloading a website, and examining the requests, status codes, and resource types.

## Practical Task: Inspecting Network Requests

**Steps:**

1. Open Google Chrome and visit any website, such as `https://example.com`.
2. Open Chrome DevTools by pressing `F12` on a computer, or by right-clicking the page and selecting **Inspect**.
3. Select the **Network** tab.
4. Reload the webpage while the Network tab is open.
5. Observe the requests, status codes, resource types, and loading times.
6. Take a screenshot of the Network tab and attach it to this assignment.

**Screenshot:** Attach your own screenshot of the Network tab here.

**Conclusion:** A website works through communication between a client and a server. The browser sends requests, the server processes them and returns responses, and the browser displays the resulting webpage. Chrome DevTools helps us understand this communication by showing network activity.