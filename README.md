# CSE134B-SS20-HW1
# Name: Daniil Katulevskiy
# PID: A17481234

## Part 1

### Q1

https://poetic-otter-361852.netlify.app/

![image](https://github.com/user-attachments/assets/e8250352-b0ca-4548-b137-927724c5643f)

### Q2

HTML 1
Font 1
Gif 1
Jpeg 2
Mp4 1
Png 1
JS 1
CSS 1
SVG/XML 6
Favicon 1

Total 16 requests

Total bytes sent
6.7 MB transferred
6.9 MB resources

![image](https://github.com/user-attachments/assets/6d12b5f7-20a2-4cf2-97b4-00ffa9197e44)

## Part 2

### Q1

espn: can't get to top headlines section, infinitely scrolls feed instead

webaim: could easily locate the virtual training page, with some difficulties, it is posible to figure out that it is not archived, since if you tab, it only tabs over the links

## Part 3

### Q1

![image](https://github.com/user-attachments/assets/9df0959b-6dc1-48c8-9ac1-8f8da656fa26)

![image](https://github.com/user-attachments/assets/b756ec41-5788-4cb1-888b-b1cb9a273335)

Troubling things about uci website:

No expiration, so outdated info can be received

Cant receive content by parts because of content-type: text/html; charset=UTF-8

Some weird server info open to anyone: mod_auth_kerb/5.4

% data transfer:

UCSD:

A) Documents - 1, B) Stylesheets - 52, C) Scripts - 4, D) Fonts - 5, E) Images - 38

UCI:

A) Documents - 2, B) Stylesheets - 5, C) Scripts - 19, D) Fonts - 5, E) Images - 70

### Q2

![image](https://github.com/user-attachments/assets/607b735d-e7a3-4006-a3c2-b12ad9dd9868)

UCSD - didn't find any weird artefacts or breaking changes (possibly buttons, but did not check, since only reviewing the main page)

![image](https://github.com/user-attachments/assets/c2139e4b-ab84-421f-8eaf-d596a5e7ad4b)

Scripps - blank page

![image](https://github.com/user-attachments/assets/62d067a6-fbfa-433e-a0af-72d3b65222f5)

UCLA - parts of content missing


### Q3

yes, https://www.csuci.edu/qwerty

no, https://jpcatholic.edu/webdevhelloworld

custom 404 pages improve user experience by guiding users back to the site with helpful links or a search bar

### Q4

![image](https://github.com/user-attachments/assets/75530bc7-d3a4-402c-969e-1c4aba391c93)

it discloses sensitive paths like /api and /graphql

blocks AI and scraping bots (GPTBot, ClaudeBot) to prevent unauthorized content use for AI training or data mining


### Q5

Google Hacking uses advanced search operators to find sensitive or exposed information on websites (e.g., login pages, files, credentials).

Google Bot indexes publicly accessible pages indiscriminately, including accidentally exposed sensitive files, configuration data, or debug pages.

Avoid exposing sensitive data through public paths, properly secure endpoints with authentication, use robots.txt to prevent indexing of sensitive resources.

A poorly designed robots.txt file might inadvertently reveal sensitive paths, making them targets for Google Hacking.

### Q6

Top results are identical, some lower results differ a bit. Google just has better ui than bing, and is slightly more relevant.

### Q7

We're hiring! https://medium.com/jobs-at-medium/work-at-medium-959d1a85284e

Filtering out curious and knowledgeable candidates.

![image](https://github.com/user-attachments/assets/9945214a-81ab-4393-a487-47d9214b8394)

These values help Medium enforce its subscription model, track user engagement, and personalize content while monitoring compliance with its free-tier limits.

### Q8

![image](https://github.com/user-attachments/assets/0b6172b3-8ade-4964-8801-e1d5ffb297dc)

Adds trending searches

### Q9

x-content-type-options: nosniff - Prevents type sniffing.

x-download-options: noopen - Prevents auto-opening of downloads.

x-frame-options: DENY - Blocks iframe embedding (prevents clickjacking).

x-permitted-cross-domain-policies: none - Restricts cross-domain data for plugins.

x-render-origin-server: Render - Identifies the origin server for debugging.

x-xss-protection: 0 - Disables outdated XSS protection.

### Q10

![image](https://github.com/user-attachments/assets/f4eac19b-7e38-44e4-8de6-b22be03cb0f5)

Eliminate Render-Blocking Resources: Defer non-critical JS/CSS to improve load speed.

Enable Text Compression: Use Gzip/Brotli to reduce resource sizes and loading times.

Properly Size Images: Resize images to match display dimensions, saving 1,329 KiB.

![image](https://github.com/user-attachments/assets/4e682733-1c06-4844-84be-0ae30d0f87de)

sdsu has lower performance score, so needs more work

### Q11

Chrome: https://chromestatus.com/

Firefox: https://platform-status.mozilla.org/

Edge: https://dev.windows.com/microsoft-edge/platform/status/

Safari: https://webkit.org/status/

Chrome Version for Shadow DOM v1: Chrome 53.

Shadow DOM v1 Release Date: August 31, 2016.

Chrome Age: First released on September 2, 2008 (16 years old).

### Q12

![image](https://github.com/user-attachments/assets/a603ba34-da1a-4c26-b647-c924d36aedb2)

Couldn't load the page. We should support adequately legacy browsers, but have a limit on how old they can be for testing purposes.

### Q13

X-Content-Type-Options: nosniff ensures files are treated strictly as their declared content type, reducing security risks. 

Cloudflare is a platform providing DDoS protection, CDN services, SSL/TLS encryption, and performance optimization for websites.

### Q14

UCSD: one, myfonts.net

SDSU: six, sdsu.edu, youtube.com, google.com
