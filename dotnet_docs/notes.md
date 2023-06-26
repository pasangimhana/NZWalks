### 2023-06-26

Program starts running in the Program.cs file.
We can add dependancies inside the Program.cs file.
Top section of the file is to create a builder.
Then we can inject services into the builder.
Then we can build the builder.
Then we can run the builder.

The next functions create the HTTP request pipeline.
Middleware is a software that assemble a pipeline to configure request and response.

In ASP.NET Core API, an HTTP pipeline refers to the series of middleware components that process HTTP requests and generate responses. The pipeline is responsible for handling and routing incoming requests to the appropriate endpoint, performing any necessary processing or transformations, and returning the corresponding HTTP response.