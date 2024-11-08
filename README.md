
 **Configure the project with CMake:**

```bash
mkdir build && cd build
cmake ..
```

 **Build the project:**

```bash
cmake --build .
```

## Available Endpoints

- `GET /person`: Retrieves a list of all person entities.
- `POST /person`: Creates a new person entity.
- `GET /person/{id}`: Retrieve a person entity by id.
- `DELETE /person/{id}`: Delete a person entity by id.

