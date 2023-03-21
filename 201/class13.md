# Reading Notes

## Local Storage and How to Use it on Websites

1. Why would a developer use local storage for a web application?

    - Unlike HTTP, local storage has a state that can be recovered instead of reset the next time you open it. You can store information without forcing unique identifiers or credentials on the user.

2. What information should not be stored in local storage?

    - Information of a user such as passwords, credit card information, social security information, health information, authentication information, any sensitive information.

3. Local storage can store what type of data? How would you convert it to that type before storing?

    - Key-value pairs where they are both strings or you could store numbers, booleans, objects, arrays by converting them to strings. You can convert by using native JSON stringify and JSON parse methods. 

## Things I want to know more about

**_Modern day use cases and everyday examples for local storage_**