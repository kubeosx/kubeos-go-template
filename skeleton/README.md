# ${{ values.serviceName }}

This is a basic Go project ${{ values.serviceName }} that serves an API.

## Getting Started

### Prerequisites
- Go 1.16 or later installed on your system.

### Building the Project
Run the following command to build the project:
```bash
go build -o ${{ values.serviceName }}
```

### Running the Project
Run the following command to start the server:
```bash
./${{ values.serviceName }}
```

The server will be running on `http://localhost:8080`.

### API Endpoints
- `GET /`: Returns `Hello, World!`.