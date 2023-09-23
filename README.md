# Todo App with TypeScript, Snowpack, and HTML/CSS

This is a simple Todo App built using TypeScript, Snowpack, HTML, and CSS. It provides a basic interface for managing your tasks, allowing you to add, complete, and delete tasks. This project serves as a template for getting started with modern web development tools and practices.

![Todo App Screenshot](screenshot.png)

## Features

- Add new tasks
- Mark tasks as completed
- Delete tasks
- Responsive design for various screen sizes

## Technologies Used

- TypeScript: A statically typed superset of JavaScript for enhanced code quality and tooling support.
- Snowpack: A fast, modern build tool for web applications.
- HTML: The standard markup language for creating web pages.
- CSS: Cascading Style Sheets for styling the app.

## Getting Started

### Prerequisites

Make sure you have the following tools installed on your machine:

- [Node.js](https://nodejs.org/): You will need Node.js to run the development server and build the app.
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/): npm is included with Node.js, but you can also use Yarn as your package manager.

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/todo-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-app
   ```

3. Install the project dependencies using npm or Yarn:

   ```bash
   npm install
   # or
   yarn install
   ```

### Development

To start a development server and view the app in your browser, run:

```bash
npm start
# or
yarn start
```

This will start a development server with hot module reloading. You can access the app in your web browser at `http://localhost:8080`.

### Building for Production

To build the app for production, run:

```bash
npm run build
# or
yarn build
```

This will create an optimized build of the app in the `dist` directory.

## Project Structure

- `src/`: Contains the source code for the Todo App.
  - `index.ts`: Entry point for the application.
  - `app.ts`: Main application logic.
  - `styles.css`: Styles for the app.
- `public/`: Contains static assets like the HTML template and the app icon.
- `dist/`: Contains the built and optimized app ready for deployment.

## Contributing

If you'd like to contribute to this project, please follow the standard GitHub workflow:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/my-feature` or `git checkout -b bugfix/issue-description`.
3. Make your changes and commit them with meaningful commit messages.
4. Push your changes to your fork: `git push origin feature/my-feature`.
5. Create a pull request to the `main` branch of this repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by various Todo App tutorials and examples available online.
- Thanks to the open-source community for providing the tools and libraries used in this project.


