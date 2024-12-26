# Flask Portfolio Application

This is a simple Flask application that serves a personal portfolio page. The application is designed to showcase your skills, projects, and contact information.

## Features

- Dynamic routing using Flask
- Tailwind CSS for modern and responsive design
- Organized project structure for easy development and deployment

## Directory Structure

```
project/
├── app.py                  # Flask application
├── templates/              # Flask templates folder
│   └── introduction.html   # Your HTML template
├── requirements.txt        # Python dependencies
```

## Prerequisites

- Python 3.7 or higher
- Pip (Python package manager)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scriptsctivate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Running the Application Locally

1. Start the Flask application:

   ```bash
   python app.py
   ```

2. Open your browser and navigate to:

   ```
   http://127.0.0.1:8080/
   ```

## Deployment

### Render

1. Push your code to a GitHub repository.
2. Log in to [Render](https://render.com) and create a new web service.
3. Configure the following settings:
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `python app.py`
4. Wait for deployment and access your app at the provided URL.

### Railway

1. Push your code to a GitHub repository.
2. Log in to [Railway](https://railway.app) and link your repository.
3. Configure the service to use Python and install dependencies.
4. Deploy and access your app.

### Deta

1. Install Deta CLI:
   ```bash
   pip install deta
   ```
2. Login to Deta:
   ```bash
   deta login
   ```
3. Deploy your project:
   ```bash
   deta deploy
   ```
4. Access your app at the Deta-provided URL.

## Environment Variables

For deployment, ensure you set the following environment variables if required by the hosting platform:

- `PORT`: The port number on which the app should run (default is 8080).

## Technologies Used

- **Flask**: Python web framework for building the backend.
- **Tailwind CSS**: Modern CSS framework for responsive and utility-first design.
- **HTML5**: Structure and content of the portfolio page.

## Author

**Tanveer Hussain**

- **Email**: [agapaitnanveermou@gmail.com](mailto:agapaitnanveermou@gmail.com)
- **LinkedIn**: [Tanveer Hussain](https://www.linkedin.com/in/tanveer-hussain-277119196/)
- **GitHub**: [GitHub Profile](https://github.com/tannu64)

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.
