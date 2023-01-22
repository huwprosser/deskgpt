# DeskGPT - A lightweight desktop ChatGPT Wrapper

Built this for me and he team at [Carter](https://carterapi.com) to move faster in our day-to-day. Thought it was worth sharing.

This is an open-source Electron app that acts as a simple wrapper around the ChatGPT API. It allows you to interact with the API and receive responses from the GPT-3 model through an easy-to-use user interface.

This codebase was a collaboration between [Huw Prosser](https://github.com/huwprosser) and ChatGPT.

Download MacOS executable [HERE](https://drive.google.com/file/d/1jXXEfS9Xb65M68uj9URC6cUdp7X91RVG/view?usp=sharing)

Or build for your machine below.

## Features

-   Simple codebase
-   Add to your Mac or Windows dock for quick access
-   One less Chrome Tab!

## Installation

1. Clone the repository
   `bash git clone https://github.com/huwprosser/deskgpt.git`

Install the necessary dependencies by running the following command in the root directory of the project
Copy code
`npm install`
Start the app by running the following command
Copy code
`npm start`
Packaging for distribution
You can use Electron Packager to package the app for distribution.

Install Electron Packager globally by running the command
Copy code
`npm install electron-packager -g`

2. Navigate to the root directory of the project in the terminal and run the following command
   Copy code
   `electron-packager . --platform=win32 --arch=x64`

This will create a executable file of your app in a folder named 'YourApp-win32-x64' in the root directory.
You can replace the platform and arch options according to your target platform and architecture.

Contributions
This is an open-source project and contributions are welcome. Feel free to submit pull requests or open an issue if you find any bugs or have any suggestions for new features.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Copy code

You may want to add more details such as screenshots, GIFs, or code snippets to make it more informative and easy to understand. Also, you should add your own details such as the repository link, your name or organization and any other specific information that might be necessary.

Please let me know if you have any other question or need any further help.
