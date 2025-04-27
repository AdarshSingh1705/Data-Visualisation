# Get-it-Visualized Backend

Data Visualization API for the Get-it-Visualized project.

---

## Overview
This backend provides RESTful APIs for data visualization, processing, and management. It is designed to work seamlessly with the frontend client, enabling users to upload data, generate charts, and retrieve visual insights.

## Features
- Upload and process datasets
- Generate various types of charts and visualizations
- User authentication and authorization
- API endpoints for data retrieval and management
- Error handling and validation

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/AdarshSingh1705/Get-it-Visualized.git
   cd Get-it-Visualized-main/backend
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up environment variables:**
   - Create a `.env` file if needed and configure your settings (database, secret keys, etc).

4. **Run the backend server:**
   ```bash
   python app.py
   ```

## Usage
- Access API endpoints at `http://localhost:<port>/api/`
- Refer to the API documentation or source code for endpoint details.

## API Endpoints (Examples)
- `POST /api/upload` — Upload a dataset
- `GET /api/charts` — Retrieve available chart types
- `POST /api/visualize` — Generate a chart from uploaded data
- `GET /api/data` — Fetch processed data


## Contributing
Contributions are welcome! Please open issues or pull requests for improvements or bug fixes.

## Contact
**Author:** Adarsh Singh  
For questions or support, open an issue or email: as.adarshsingh13@email.com

---

