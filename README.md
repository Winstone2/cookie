# cookie
    Understanding Cookies: Cookies are small pieces of data stored in the user's browser. They are often used to remember user preferences, authentication data, and other information. Cookies are sent between the browser and the server with each HTTP request, allowing the server to recognize the user.

    Setting a Cookie: To set a cookie, you use the document.cookie property. It allows you to add a new cookie or update an existing one. A cookie is typically a string containing a key-value pair, expiration date, domain, and other optional parameters.

    Getting a Cookie: To retrieve the value of a cookie, you can read the document.cookie property. The property will return a string containing all the cookies for the current domain, separated by semicolons. You will need to parse this string to extract the desired cookie's value.

    Expiry and Persistence: Cookies can have an expiration date, after which they will no longer be valid. Some cookies are session-based and expire when the browser session ends, while others can have a specific expiry date.

    Security Considerations: Be mindful of the data you store in cookies, as they are visible to the user and could be manipulated. Avoid storing sensitive information in cookies.
    In this example, we defined two functions, setCookie and getCookie. The setCookie function takes the name, value, and number of days until expiration as parameters and sets a new cookie with those details. The getCookie function takes the name of the cookie and retrieves its value.

Remember that this example does not cover securing sensitive data or handling cookie manipulation, so in a real-world scenario, you'd need to consider security measures as well.
