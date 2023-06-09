# GPT-3 React Website

This is a GitHub repository for a React website that showcases the capabilities of OpenAI's GPT-3 language model. The website provides an interface where users can interact with GPT-3 and witness its natural language processing abilities.




## Features
- **GPT-3 Text Generation**: Users can enter prompts or questions, and GPT-3 will generate text-based responses.
- **Natural Language Understanding**: GPT-3 can understand and respond to a wide range of queries, providing meaningful and context-aware answers.
- **Real-Time Interaction**: The website utilizes WebSocket connections to enable real-time communication with GPT-3, making the conversation experience seamless and dynamic.
- **Easy Integration**: The React components and hooks provided in this repository make it easy to integrate GPT-3 functionality into your own React projects.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Ryan-Power/GPT3-Website.git
   ```

2. Navigate to the project directory:

   ```bash
   cd gpt-3-react-website
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Configure OpenAI API access:
   
   - Obtain an API key from OpenAI. Visit their [website](https://openai.com/) for more information.
   - Create a `.env` file in the project root directory.
   - Add the following line to the `.env` file, replacing `YOUR_API_KEY` with your actual OpenAI API key:

     ```
     REACT_APP_OPENAI_API_KEY=YOUR_API_KEY
     ```

5. Start the development server:

   ```bash
   npm start
   ```

6. Open your browser and visit `http://localhost:3000` to see the website in action.

## Usage
Once the website is up and running, you can enter prompts or questions in the provided input field and observe the responses generated by GPT-3. The website will maintain a dynamic conversation flow, allowing you to have an interactive experience with the language model.

Feel free to explore the codebase to understand how the GPT-3 interactions are implemented using the OpenAI API. The React components and hooks provided in this repository can also be reused in your own projects to integrate GPT-3 functionality.

## Contributing
Contributions to this project are welcome. If you encounter any issues or have ideas for improvements, feel free to open an issue or submit a pull request. Please ensure that you follow the existing code style and provide detailed information about your changes.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.