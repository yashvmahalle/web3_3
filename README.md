 HTML Meta Tag Redirection Example

This repository contains an example of how to use the `<meta>` tag in HTML to create a redirection. The provided HTML file redirects users to Masai School's investors page after a delay of 10 seconds.

## How to Use the Meta Tag for Redirection

The `<meta>` tag can be used to set metadata about an HTML document. One of its uses is to redirect users to a different URL after a specified time. 

### Syntax

```html
<meta http-equiv="refresh" content="seconds; url='your-url-here'" />
seconds: The number of seconds to wait before redirecting.
url: The URL to redirect to.
Example
In this example, we will redirect users to Masai School's investors page (https://masaischool.com/investors) after a delay of 10 seconds.

index.html
The index.html file contains the following code:

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirecting to Masai School</title>
    <meta http-equiv="refresh" content="10; url='https://masaischool.com/investors'" />
</head>
<body>
    <h1>Thank you for visiting!</h1>
    <p>You will be redirected to Masai School's investors page in 10 seconds...</p>
</body>
</html>
How to Run
Clone the repository to your local machine.
bash
Copy code
git clone https://github.com/yourusername/meta-tag-redirect.git
Navigate to the project directory.
bash
Copy code
cd meta-tag-redirect
Open index.html in your web browser.
Contribution
Feel free to fork the repository and submit pull requests for any improvements or bug fixes.

