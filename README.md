## Overview

This project, **IU Course Compass AI API**, is designed to provide intelligent course recommendations and insights for students at Indiana University. By leveraging advanced AI algorithms, the API helps students make informed decisions about their academic journey.

## Features

- **Personalized Course Recommendations**: Tailored suggestions based on user preferences and academic history.
- **Search Functionality**: Quickly find courses by keywords, departments, or instructors.
- **Data Insights**: Analyze course trends, popularity, and performance metrics.
- **Integration Ready**: Easy to integrate with existing university systems.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/iu-course-compass-ai-api.git
    ```
2. Navigate to the project directory:
    ```bash
    cd iu-Course-compass-ai-API
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start the server:
    ```bash
    fastapi dev main.py
    ```
2. Access the API at `http://localhost:8000`.

## API Endpoints

- `GET /courses`: Retrieve a list of available courses.
- `POST /chat`: Personalised chat with the AI Agent.
- `GET /health`: Check if the API is running perfectly or not.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Add feature-name"
    ```
4. Push to your branch:
    ```bash
    git push origin feature-name
    ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
