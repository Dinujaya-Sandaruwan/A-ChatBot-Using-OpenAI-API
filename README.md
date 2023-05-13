# OpenAI Chat Application

This is a chat application built using OpenAI's API, designed to provide users with an engaging and intuitive conversation experience with a sophisticated AI language model. Users can chat about anything they like and receive contextually appropriate and linguistically fluent responses generated by the OpenAI API.

![image](https://github.com/Dinujaya-Sandaruwan/A-ChatBot-Using-OpenAI-API/assets/88492493/1113b724-b34d-43f6-9ff5-c884ca5733ec)


## Technologies Used

-   Vanilla JS: for the client-side of the application.
-   API: The application is powered by OpenAI's API to handle the natural language processing and generation of the responses.
-   Node.js: A JavaScript runtime environment used for the backend server of the application.
-   Vite: A fast build tool used to bundle the client-side of the application.
-   Dependencies: The project depends on the following packages:
    -   cors: Enables Cross-Origin Resource Sharing (CORS) for the backend server.
    -   dotenv: Loads environment variables from a .env file into the application.
    -   express: A minimalist web framework used for the backend server.
    -   nodemon: A utility used to monitor changes in the application and automatically restart the server.
    -   openai: A package that provides a simple interface to interact with the OpenAI API.

## Installation and Usage

1.  Clone the project repository.
2.  Create a `.env` file in the project root and provide the following environment variables:
    -   `OPENAI_API_KEY`: Your OpenAI API key.
    -   `PORT`: The port on which to run the backend server (default is 3000).
3.  Run `npm install` to install the dependencies.
4.  Run `npm run dev` to start the development server.
5.  Open `http://localhost:3000` in your browser to access the chat application.

## Future Work

Some possible features to add in the future are:

-   Authentication and user accounts to save conversation history.
-   Better error handling and user feedback.
-   Additional functionalities such as providing contextual information to the AI model.

## Contributing

Contributions to this project are welcome. Feel free to create a pull request or submit an issue if you have any suggestions, feedback, or problems with the application.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
