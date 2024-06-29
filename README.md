# SkyCastAPI

SkyCastAPI is a Python-based project that provides real-time weather forecasts for various locations. It integrates with a Weather API to retrieve accurate weather data efficiently.

## Features

- Provides real-time weather forecasts.
- Displays country-specific temperature data.
- Offers brief weather descriptions.

## Technologies Used

- Python
- Weather API with API Key

## Installation

1. Clone the repository:
    ```bash
   https://github.com/Dishika18/SkyCastAPI.git
    ```

2. Navigate to the project directory:
    ```bash
    cd skycastapi
    ```

3. Create a virtual environment:
    ```bash
    python -m venv env
    ```

## Usage

1. Obtain your API key from the Weather API provider.
2. Create a `.env` file in the project directory and add your API key:
    ```env
    API_KEY=your_api_key_here
    ```

3. Run the application:
    ```bash
    python main.py
    ```

4. Follow the on-screen prompts to get weather forecasts for your desired locations.

## Example

After running `python main.py`, you will be prompted to enter a location. The application will then display the current weather, including temperature and a brief description.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes.
4. Commit your changes:
    ```bash
    git commit -m "Add your feature"
    ```
5. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
6. Open a pull request.
