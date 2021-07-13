# Lictor.dev server


# Folder structure
**Controllers:** handle the requests arriving, the further calls to the services and below layers, and the delivery of the responses. 

database: setup DB (e.g., SQL schema) and host direct connection to our Postgres database.

repositories: database operation management, handles C(R?)UD logic.

services: handle the business logic of data operations, e.g., validation, transformation, etc.

# Deployment
Heroku buildpack: https://github.com/chibat/heroku-buildpack-deno.git