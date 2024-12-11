# Pastebin API

Hey all! This is a simple Pastebin API that allows you to create and retrieve pastes. 

## Setup Instructions

1. **Clone the repository** (if applicable):
   ```bash
   git clone <your-repo-url>
   cd <your-repo-directory>
   ```

2. **Configure the application:**

Open app.py and set the following variables:
WEBHOOK: Add your host URL.
MONGO_URL: Add your MongoDB connection string. You can get this from the MongoDB website.

3. **Install the required packages:**

```bash
pip install -r requirements
```

4. **Run the application:**

```bash
python3 app.py
```


**Response**
The API will return a JSON response containing the URL to access your paste and the raw content URL. For example:

```json
{
    "url": "https://your-host-url/paste/<paste_id>",
    "raw": "https://your-host-url/raw/<paste_id>"
}
```
