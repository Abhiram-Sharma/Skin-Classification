# Skin App

Skin App is a web application developed using [Streamlit](https://streamlit.io/) that provides users with an intuitive interface to interact with skin-related functionalities. The project is deployed at [Skin App](https://skin-app.streamlit.app/).

## Features

- **User-Friendly Interface:** Utilizes Streamlit to offer a simple and responsive UI.
- **Real-Time Interaction:** Enables users to access and analyze skin-related insights (customize this section based on your app's specific functionality).
- **Easy Deployment:** Containerized setup with development container support for a streamlined development workflow.

## Installation

### Prerequisites

- **Python 3.7 or later**
- **APT Dependencies:** Check `apt.txt` for the required APT packages.
- **Additional System Packages:** Listed in `packages.txt`.

### Python Dependencies

Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

## Running the Application Locally

Once the dependencies are installed, start the application with the following command:

```bash
streamlit run skin_app.py
```

The app will launch in your default web browser at [http://localhost:8501](http://localhost:8501).

## Development Setup

The project includes a development container configuration (`.devcontainer/`) that allows you to use Visual Studio Code's Remote Containers feature for a consistent development environment.

### Using VS Code Remote Containers

1. Install [Visual Studio Code](https://code.visualstudio.com/) and the [Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).
2. Open the project in VS Code.
3. Use the command palette (`F1` > **Remote-Containers: Reopen in Container**) to reopen the project inside the container.

## Project Structure

```
├── .devcontainer/
│   └── devcontainer.json       # Container configuration for VS Code
├── apt.txt                     # APT dependencies list
├── packages.txt                # Additional system package dependencies
├── requirements.txt            # Python dependencies
├── skin_app.py                 # Main Streamlit application file
└── README.md                   # Project documentation
```

## Deployment

The application is deployed on Streamlit's sharing platform. Visit the live app at [Skin App](https://skin-app.streamlit.app/).

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). *(Include your actual license file if applicable.)*

## Contact

For further questions or support, please reach out via email at [ab23.ar39@gmail.com](mailto:ab23.ar39@gmail.com).
```

---
