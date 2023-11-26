# News24*7

Crafted a ReactJS-based news application, leveraging reusable components and the NewsAPI, to facilitate the presentation and preview of news articles from diverse sources. The app not only showcases the latest and trending news on its homepage but also provides access to up-to-the-minute breaking news and articles from a wide array of online news sources and blogs.

## Intended Use of the System:
1. Users: The intended users of the system are individuals interested in staying updated with the latest news and articles from various sources and blogs. This can include a wide range of people, such as news enthusiasts, professionals, students, or anyone seeking current information.

2. How They Will Use the System:
Users will access the news application through a web browser or a similar client-side   interface.
They will be able to search for news articles from various sources.
Users can browse through categories or topics of interest.
The system will display the latest and trending news articles on the home page.
Users can click on news articles to read the full content.
Additionally, they can preview news articles without leaving the application.

## Overall Functionality:
The system's primary functionality is to provide a user-friendly interface for accessing and reading news articles from a wide range of sources and blogs. Users can accomplish the following tasks:
1. Browse News: Users can explore news articles from diverse sources and categories.
2. Search: They can search for specific news articles or topics of interest.
3. Preview: Users can get a quick preview of news articles without navigating away from the application.
4. Read Full Articles: By clicking on articles, users can access the complete content.
5. Stay Updated: The home page showcases the latest and trending news to keep users informed.

## Main Components of the System:
The system can be logically broken down into several main components:
1. User Interface (UI):
This component is responsible for rendering the web application and interacting with users.
It includes the user interface elements such as search bars, navigation menus, and article previews.
Rationale: Separating the UI component allows for a clean and intuitive user experience.
2.  API Integration:
This component manages the integration with external news APIs, such as NewsAPI or MediaStack, to fetch news data.
It includes modules for making API requests, handling responses, and formatting data for display.
Rationale: Separating API integration ensures that the application can fetch and update news data independently from the UI.
3.  Data Storage:
This component is responsible for storing and caching news data, including articles and their metadata.
It may involve a local database or storage system to reduce the need for repefcated API calls.
Rationale: Caching data locally enhances performance and reduces the load on external APIs.
4. Routing and Navigation:
This component manages the routing within the application, ensuring that users can navigate between different sections and articles.
It includes routing logic and URL handling.
Rationale: Separating routing helps in creating a structured and organized user flow.
5.  Presentation and Rendering:
This component focuses on rendering news articles, previews, and user interface elements based on the data received from the API.
It includes templates, components, and views for displaying content.
 Rationale: Separating presentation logic from data retrieval ensures flexibility and maintainability.
The breakdown of these components allows for modularity, scalability, and maintainability in the development of the news application. It ensures that each aspect of the system can be developed, tested, and maintained independently, leading to a robust and user-friendly application.

## Designing Key Features of UI:
- Home Page:
Display latest news articles in a visually appealing format.
Include a search bar for users to initiate searches.

- Search Results Page:
Show search results matching user queries.
Provide options for previewing articles or viewing full content.

- Article Preview:
Display a concise preview of a selected news article.
Include options for users to read the full article.

- Full Article View:
Present the complete content of a selected news article in a readable format.


## Deploying/Installing the System:

### Prerequisites:
- Node.js installed on the deployment machine.
- Package manager (e.g., npm or yarn) for installing dependencies.
-  to the codebase from a version control system like Git.

### Steps:

- Clone the Repository:
```
git clone [repository_url]
```
- Navigate to the Project Directory: 
```
cd [project_directory]
```

- Install Dependencies:
```
npm install
```

- Build the React App:
```
npm run build
``````

- Start the Application:
```
npm start
```
This will launch the application on a local development server.

### Access the Application:
Open a web browser and go to http://localhost:3000 (or the specified port).

### Technical Specifications:

- Frontend Framework:
React (version 16.13.1)
React is a JavaScript library for building user interfaces, and version 16.13.1 is the specific version your project is using.

- UI Component Library:
Ant Design (version 4.4.2)
Ant Design is a popular React UI component library that provides a set of high-quality components for building modern web applications.

- HTTP Client:
Axios (version 0.19.2)
Axios is used for making HTTP requests from the React application to interact with APIs. It simplifies the process of handling asynchronous operations.

-  Parsing:
React HTML Parser (version 2.0.2)
React HTML Parser is a library used for converting HTML strings into React elements. It's helpful when you need to render HTML content received from an API.

- Testing Utilities:
```
@testing-library/jest-dom (version 4.2.4)
@testing-library/react (version 9.5.0)
@testing-library/user-event (version 7.2.1)
```

These testing libraries provide utilities for testing React components using Jest. They facilitate writing tests for component behavior and interactions.

- Build Tool and Scripts:
React Scripts (version 3.4.1)
The React Scripts package provides scripts for building, testing, and running a React application. It abstracts many configuration details, making it easier to manage the development workflow.

- Deployment:
Yet to decide

- ESLint Configuration:
ESLint is configured to extend the "react-app" configuration. This ensures that the code follows the recommended coding style and practices for React applications.

- Browserslist Configuration:
Specifies the target browsers for which the application should be compatible in production and development environments. This information is used by Autoprefixer and other tools to adjust the CSS output.

- Node.js and npm:
The project relies on Node.js and npm for managing dependencies and running scripts. Ensure that the target environment has the appropriate versions installed.


### Main Features:

- Efficient News Display:
Users can view the latest news on the home page.
News data is formatted and structured for better presentation.

- Search Functionality:
Users can filter for news articles based on specific topics or keywords like region, tech trends, top news.
Preview and Full Content:
Users can preview news articles before deciding to read the full content.
Access to the complete content of news articles is provided.

### Walkthrough for Main Scenario:

Homepage:
- Accessing the application, users are greeted with the latest news displayed on the homepage.
-  Also, seen is the preview of the news in a tabular manner.
- Also, a collapsed closed sidebar is seen which allows users to choose the source of news.
