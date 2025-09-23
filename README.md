# api-authentication
- TODO 1: Fill in your values for the 3 types of auth.
- TODO 2: Use axios to hit up the /random endpoint
  - The data you get back should be sent to the ejs file as "content"
  - Hint: make sure you use JSON.stringify to turn the JS object from axios into a string.
- TODO 3: Write your code here to hit up the /all endpoint
  - Specify that you only want the secrets from page 2
  - HINT: This is how you can use axios to do basic auth:
  - https://stackoverflow.com/a/74632908

  ``` 
   axios.get(URL, {
      auth: {
        username: "abc",
        password: "123",
      },
    });
  ```
- TODO 4: Write your code here to hit up the /filter endpoint
  - Filter for all secrets with an embarassment score of 5 or greater
  - HINT: You need to provide a query parameter of apiKey in the request.

- TODO 5: Write your code here to hit up the /secrets/{id} endpoint
  - and get the secret with id of 42
  - HINT: This is how you can use axios to do bearer token auth:
  - https://stackoverflow.com/a/52645402
  ```
  axios.get(URL, {
    headers: { 
      Authorization: `Bearer <YOUR TOKEN HERE>` 
    },
  });
  ```

