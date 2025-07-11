# Metadata Cheat Sheet 📚

## HTML `<meta>` Tags ⚙️

Earlier in the course, you learned about meta tags and how they can help convey information to search engines, improving how pages are categorized. Keep this cheat sheet handy when building your web applications! 🧰

### Meta Tag Structure 🏗️
1. **Name**: The name of the property (e.g., `author`, `description`, `robots`).
2. **Content**: Specifies the value for the property (e.g., `author="name"`, `content="This is a description"`).

### Types of Meta Tags 🔍

#### Basic Meta Tags (For SEO) 📈
- `<meta name="description" content="..."/>`
    - Provides a brief description of the web page.

- `<meta name="title" content="..."/>`
    - Specifies the title of the web page.

- `<meta name="author" content="name"/>`
    - Specifies the author of the web page.

- `<meta name="language" content="english"/>`
    - Specifies the language of the web page.

- `<meta name="robots" content="index,follow"/>`
    - Instructs search engines how to crawl or index the page.

- `<meta name="google" content="..."/>`
    - Tells Google not to show the sitelinks search box for your page in search results.

- `<meta name="googlebot" content="notranslate"/>`
    - Tells Google you don’t want to offer automatic translation for your page if the user is browsing in a different language.

- `<meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm"/>`
    - Specifies the last modified date of the page.

- `<meta name="rating" content="safe for kids"/>`
    - Specifies the expected audience for the page.

- `<meta name="copyright" content="Copyright 2022"/>`
    - Specifies copyright information for the page.

#### `<meta http-equiv="..."/>` Tags 🌐
- `<meta http-equiv="content-type" content="text/html"/>`
    - Specifies the format of the document returned by the server.

- `<meta http-equiv="default-style" content="..."/>`
    - Specifies the format of the styling document.

- `<meta http-equiv="refresh" content="30"/>`
    - Refreshes the page every 30 seconds (be cautious!).

- `<meta http-equiv="Content-language" content="en"/>`
    - Specifies the language of the page.

- `<meta http-equiv="Cache-Control" content="no-cache"/>`
    - Instructs the browser how to cache your page.

#### Responsive Design / Mobile Meta Tags 📱
- `<meta name="format-detection" content="telephone=yes"/>`
    - Turns phone numbers into clickable links for calling.

- `<meta name="HandheldFriendly" content="true"/>`
    - Specifies that the page is optimized for mobile devices.

- `<meta name="viewport" content="width=device-width, initial-scale=1.0"/>`
    - Defines the visible area of the window, ensuring the content looks good on all screen sizes.

### Charset 🔠
- `<meta charset="UTF-8"/>`
    - Specifies the character encoding used for the page (UTF-8 is most common).

### HTTP-equiv (Simulating HTTP Headers) 🌍
- `<meta http-equiv="refresh" content="30"/>`
    - Refreshes the page after 30 seconds.

### Final Notes 📝
- The `meta` tags provide crucial information for browsers, search engines, and users to better interact with your web page.
- Use these tags strategically to optimize for SEO, mobile responsiveness, and more! 🚀

---

Happy coding! 🎉
