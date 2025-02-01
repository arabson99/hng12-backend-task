# HNG12 Backend Task

This is a simple API that returns basic information as part of the HNG12 Stage 0 Backend Task.

## 🚀 API URL
- **Live URL**: [https://hng12-api.onrender.com](https://hng12-api.onrender.com)

## Endpoit
- **GET** `/`

## 🛠 Setup Instructions
1. Clone the repo:
   ```sh
   git clone https://github.com/arabson99/hng12-backend-task.git
   cd hng12-backend-task
   ```

2. Install dependencies:
    ```
    pip install fastapi uvicorn

    ```

3. Run the API locally:
    ```
    uvicorn main:app --host 0.0.0.0 --port 8000 --reload
    ```

4. Test API:
    - Visit: http://127.0.0.1:8000
    - Swagger Docs: http://127.0.0.1:8000/docs

    ## API Response Format
    GET `/`
    ```
        {
        "email": "arabiusman99@gmail.com",
        "current_datetime": "2025-01-30T09:30:00Z",
        "github_url": "https://github.com/yourusername/hng12-backend-task"
        }
    ```


