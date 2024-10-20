# URL Redirection Project

## Overview
This project demonstrates two methods of redirecting users from one webpage to another. The first method uses JavaScript for client-side redirection, while the second method employs the HTML meta refresh technique. 

## Project Structure

```
url-redirection-explorer/
├── index.html
└── page/
   └── index.html
```

## Files

### 1. `index.html` (Meta Refresh Method)
This file uses the HTML meta refresh method to redirect users to a new URL after a specified delay. Here’s a brief code snippet from the file:

```html
<meta http-equiv="refresh" content="0; URL='https://example.com'" />
```
- **How it works**: The `meta` tag instructs the browser to redirect to the specified URL after a specified delay (0 seconds in this case for an immediate redirect).

### 2. `page/index.html` (JavaScript Redirect Method)
This file implements a JavaScript redirect to send users to a new URL immediately upon loading the page. Here’s a brief code snippet from the file:

```html
<script>
    window.location.href = "https://example.com";
</script>
```
- **How it works**: The JavaScript `window.location.href` command sets the current page’s URL to the specified one, effectively redirecting the user immediately.

## Installation
To set up this project on your local machine, follow these steps:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd URL-REDIRECTION-EXAMPLE
   ```
3. Open the `index.html` file in your browser to see the meta refresh in action.
4. Open the `page/index.html` file in your browser to see the JavaScript redirect.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Feel free to submit issues or pull requests if you have suggestions for improvements or additional features.