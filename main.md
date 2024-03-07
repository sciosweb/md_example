## REST API Endpoint Usage

To interact with a REST API, you need to make HTTP requests to specific endpoints. Each endpoint represents a specific resource or functionality provided by the API. Here's a breakdown of the common HTTP methods used in REST API endpoint usage:

- **GET**: Used to retrieve data from the server. For example, `GET /users` retrieves a list of all users.

- **POST**: Used to send data to the server to create a new resource. For example, `POST /users` creates a new user.

- **PUT**: Used to update an existing resource on the server. For example, `PUT /users/{id}` updates the user with the specified ID.

- **DELETE**: Used to delete a resource from the server. For example, `DELETE /users/{id}` deletes the user with the specified ID.

In addition to the HTTP methods, REST API endpoints often include parameters to provide additional information or filter the results. These parameters can be passed as query parameters or in the request body, depending on the API design.

For example, to retrieve a specific user with ID 123, you would make a GET request to `/users/123`. If you want to filter the results to only include active users, you might use a query parameter like `/users?status=active`.

It's important to refer to the API documentation to understand the available endpoints, their required parameters, and the expected response format.

Remember to include any necessary authentication headers or tokens when making requests to secure APIs.

