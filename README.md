# Dekstop E-Library 2021

Elibrary_App is a Python-based application developed using the Kivy framework and KivyMD for the user interface. This application allows users to manage an electronic library, including parsing book information, managing icons, and saving parsed images.

## Project Structure
\
Here's a comprehensive README.md file for your Elibrary_App project, including the project structure, installation steps, usage instructions, and more.

README.md Content
markdown
Копировать код
# Elibrary_App

Elibrary_App is a Python-based application developed using the Kivy framework and KivyMD for the user interface. This application allows users to manage an electronic library, including parsing book information, managing icons, and saving parsed images.

## Project Structure

Elibrary_App/
├── Library/
├── app/
│ ├── fonts/
│ ├── images/
│ ├── bookparser.py
│ ├── funktions_for_lib.py
│ ├── kivymd_icons.py
│ ├── lib_kivy_file.kv
│ ├── lib_python_file.py
│ └── save_pasedimages.py
└── requirements.txt


Where lib_python_file.py is main fiel to start and activate dekstop application. Other files are used to parse and save information about books from websites inculding names, images, years...


## Installation

### Prerequisites

Ensure you have Python 3.x installed on your system.

### Steps

1. **Clone the repository**:
    ```sh
    git clone https://github.com/EMIRABYBEKOV/Desktop-E-Library.git
    cd Elibrary_App
    ```

2. **Create and activate a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\\Scripts\\activate`
    ```

3. **Install the dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

To run the application, execute the following command:
```sh
python app/lib_python_file.py
```

To be honest, the app doesn't work properly due to outdated versions and compatibility issues. I wrote the project in 2021 and never managed to configure everything correctly. I decided to keep the project as a repository to showcase my past skills this year.

#Licence

This project is licensed under the MIT License.

