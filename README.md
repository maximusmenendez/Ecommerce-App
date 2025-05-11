<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# ECOMMERCE-APP

<em>Empower Your Shopping Experience, Effortlessly Simplified</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/license/maximusmenendez/Ecommerce-App?style=flat&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
<img src="https://img.shields.io/github/last-commit/maximusmenendez/Ecommerce-App?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/maximusmenendez/Ecommerce-App?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/maximusmenendez/Ecommerce-App?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Express-000000.svg?style=flat&logo=Express&logoColor=white" alt="Express">
<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
<img src="https://img.shields.io/badge/npm-CB3837.svg?style=flat&logo=npm&logoColor=white" alt="npm">
<img src="https://img.shields.io/badge/Mongoose-F04D35.svg?style=flat&logo=Mongoose&logoColor=white" alt="Mongoose">
<img src="https://img.shields.io/badge/.ENV-ECD53F.svg?style=flat&logo=dotenv&logoColor=black" alt=".ENV">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">
<br>
<img src="https://img.shields.io/badge/Nodemon-76D04B.svg?style=flat&logo=Nodemon&logoColor=white" alt="Nodemon">
<img src="https://img.shields.io/badge/React-61DAFB.svg?style=flat&logo=React&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=flat&logo=Axios&logoColor=white" alt="Axios">
<img src="https://img.shields.io/badge/Redux-764ABC.svg?style=flat&logo=Redux&logoColor=white" alt="Redux">
<img src="https://img.shields.io/badge/CSS-663399.svg?style=flat&logo=CSS&logoColor=white" alt="CSS">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)
- [Features](#features)
- [Project Structure](#project-structure)
    - [Project Index](#project-index)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgment](#acknowledgment)

---

## Overview

Ecommerce-App is a comprehensive solution for building scalable e-commerce platforms, combining robust backend services with a dynamic frontend.

**Why Ecommerce-App?**

This project streamlines the creation of e-commerce applications with powerful features and intuitive architecture. The core features include:

- **🔒 User Authentication:** Secure registration and login processes with JWT for session management.
- **📦 Dynamic Product Management:** Efficient routing for product and category management, enhancing data access.
- **🔄 Deterministic Builds:** Ensures consistent dependency versions, preventing issues from version mismatches.
- **📊 Robust State Management:** Utilizes Redux for seamless state management across the frontend, improving user experience.
- **💳 Payment Integration:** Secure payment processing through Stripe, enhancing the checkout experience.
- **📱 Responsive Design:** Built with a focus on responsive layouts, ensuring a cohesive user experience across devices.

---

## Features

|      | Component       | Details                              |
| :--- | :-------------- | :----------------------------------- |
| ⚙️  | **Architecture**  | <ul><li>Microservices architecture</li><li>Separation of frontend and backend</li><li>RESTful API design</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>ESLint for JavaScript linting</li><li>Prettier for code formatting</li><li>Consistent coding standards across components</li></ul> |
| 📄 | **Documentation** | <ul><li>README.md for project overview</li><li>API documentation in Swagger format</li><li>Inline comments for complex logic</li></ul> |
| 🔌 | **Integrations**  | <ul><li>Integration with MongoDB via Mongoose</li><li>Authentication using JWT</li><li>Payment processing with third-party APIs</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Component-based architecture in React</li><li>Redux for state management</li><li>Reusable components across the application</li></ul> |
| 🧪 | **Testing**       | <ul><li>Unit tests with Jest</li><li>Integration tests with React Testing Library</li><li>End-to-end tests with Cypress</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Code splitting for faster load times</li><li>Optimized images and assets</li><li>Lazy loading of components</li></ul> |
| 🛡️ | **Security**      | <ul><li>Environment variables for sensitive data</li><li>Password hashing with bcryptjs</li><li>Input validation with @hapi/joi</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Frontend: React, Redux, Axios</li><li>Backend: Express, Mongoose, dotenv</li><li>Development: Nodemon, ESLint, Prettier</li></ul> |
| 🚀 | **Scalability**   | <ul><li>Microservices allow independent scaling</li><li>Load balancing strategies for API requests</li><li>Database sharding for large datasets</li></ul> |

---

## Project Structure

```sh
└── Ecommerce-App/
    ├── LICENSE
    ├── backend
    │   ├── app.js
    │   ├── config
    │   ├── db.js
    │   ├── model
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── routes
    │   └── validation.js
    └── frontend
        ├── README.md
        ├── package-lock.json
        ├── package.json
        ├── public
        └── src
```

---

### Project Index

<details open>
	<summary><b><code>ECOMMERCE-APP/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/LICENSE'>LICENSE</a></b></td>
					<td style='padding: 8px;'>- The MIT License facilitates the free use, modification, and distribution of the software, ensuring that users can leverage the codebase without restrictions while maintaining proper attribution<br>- It establishes a framework for collaboration and sharing, promoting an open-source ethos that encourages innovation and community engagement, all while limiting liability for the authors.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- backend Submodule -->
	<details>
		<summary><b>backend</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ backend</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/package-lock.json'>package-lock.json</a></b></td>
					<td style='padding: 8px;'>- Project Summary## OverviewThe <code>backend/package-lock.json</code> file is a crucial component of the backend architecture of this project<br>- It serves as a comprehensive record of the exact versions of all dependencies used in the backend application, ensuring consistency and reliability across different environments<br>- By locking the dependency versions, this file helps prevent issues that may arise from version mismatches, thereby facilitating smoother development, testing, and deployment processes.## PurposeThe primary purpose of the <code>package-lock.json</code> file is to provide a deterministic build environment for the backend services<br>- It guarantees that every developer and deployment instance uses the same versions of libraries and packages, which is essential for maintaining stability and avoiding unexpected behavior in the application<br>- This file is automatically generated when dependencies are installed or updated, reflecting the current state of the project's dependency tree.In summary, the <code>backend/package-lock.json</code> file plays a vital role in the overall architecture by ensuring that the backend services operate reliably and consistently, which is fundamental for the success of the entire codebase.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/validation.js'>validation.js</a></b></td>
					<td style='padding: 8px;'>- Validation functions ensure that user input for registration and login adheres to specified criteria, enhancing data integrity and security within the application<br>- By utilizing a schema-based approach, these functions validate essential fields such as name, email, and password, thereby preventing invalid data from entering the system<br>- This contributes to the overall robustness of the backend architecture by enforcing consistent user data standards.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/db.js'>db.js</a></b></td>
					<td style='padding: 8px;'>- Establishes a connection to the MongoDB database using Mongoose, facilitating seamless data interactions within the backend architecture<br>- By leveraging environment variables for configuration, it ensures secure and flexible database connectivity<br>- This foundational component supports the overall functionality of the application, enabling efficient data management and retrieval across various services in the codebase.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/app.js'>app.js</a></b></td>
					<td style='padding: 8px;'>- Establishes the core server functionality for the backend of the application, integrating essential middleware for request handling and CORS management<br>- It defines API routes for product and user authentication, facilitating seamless communication between the frontend and backend<br>- Additionally, it serves static files in production, ensuring a cohesive user experience by delivering the frontend application alongside the API.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/package.json'>package.json</a></b></td>
					<td style='padding: 8px;'>- Backend package.json serves as the configuration hub for the backend portion of the project, defining essential metadata, scripts for development and deployment, and managing dependencies<br>- It facilitates the seamless integration of server and client components, enabling efficient development workflows and ensuring that the application can be easily built and run in various environments, including Heroku.</td>
				</tr>
			</table>
			<!-- routes Submodule -->
			<details>
				<summary><b>routes</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ backend.routes</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/routes/product.js'>product.js</a></b></td>
							<td style='padding: 8px;'>- Provides routing functionality for product and category management within the backend architecture<br>- It facilitates the retrieval of all products, all category names, and products filtered by specific category names<br>- This enhances the overall application by enabling efficient data access and organization, ensuring that users can easily navigate and interact with the product catalog based on their interests.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/routes/users.js'>users.js</a></b></td>
							<td style='padding: 8px;'>- User route management facilitates user registration, login, and retrieval of current user information within the application<br>- It ensures input validation, handles password encryption, and generates JSON Web Tokens for authenticated sessions<br>- By integrating with external libraries for avatar generation and authentication, it streamlines user interactions while maintaining security and data integrity across the backend architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/routes/cat.js'>cat.js</a></b></td>
							<td style='padding: 8px;'>- Defines routes for managing cat-related resources within the backend architecture<br>- Facilitates the creation, retrieval, updating, and deletion of cat data, ensuring seamless interaction between the client and server<br>- This component plays a crucial role in the overall functionality of the application, enabling users to engage with cat information effectively while maintaining a structured and organized codebase.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/routes/auth.js'>auth.js</a></b></td>
							<td style='padding: 8px;'>- Handles user authentication by providing registration and login endpoints<br>- It validates user input, checks for existing users, hashes passwords for security, and generates JSON Web Tokens for authenticated sessions<br>- This functionality is essential for managing user access and ensuring secure interactions within the broader application architecture, facilitating user management and protecting sensitive data.</td>
						</tr>
					</table>
				</blockquote>
			</details>
			<!-- model Submodule -->
			<details>
				<summary><b>model</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ backend.model</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/model/CatModal.js'>CatModal.js</a></b></td>
							<td style='padding: 8px;'>- Defines a Mongoose schema for managing categories within the application<br>- This schema establishes the structure for category data, ensuring that each category has a unique identifier and a required name<br>- By integrating with the broader codebase, it facilitates efficient data handling and storage, contributing to the overall functionality of the backend architecture in organizing and retrieving category-related information.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/model/User.js'>User.js</a></b></td>
							<td style='padding: 8px;'>- Defines a user model for the application, establishing the structure and requirements for user data within the database<br>- It encapsulates essential user attributes such as name, email, password, and registration date, ensuring data integrity and facilitating user management<br>- This model serves as a foundational component of the backend architecture, enabling seamless interactions with user-related functionalities throughout the codebase.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/model/ProductModal.js'>ProductModal.js</a></b></td>
							<td style='padding: 8px;'>- Defines a Mongoose schema for managing product data within the application<br>- It establishes the structure for product entries, including essential attributes such as title, route name, and associated items<br>- This schema facilitates the organization and retrieval of product information, ensuring consistency and integrity across the backend architecture, ultimately supporting the overall functionality of the e-commerce platform.</td>
						</tr>
					</table>
				</blockquote>
			</details>
			<!-- config Submodule -->
			<details>
				<summary><b>config</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ backend.config</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/config/keys_dev.js'>keys_dev.js</a></b></td>
							<td style='padding: 8px;'>- Configuration settings for the development environment are defined, facilitating seamless integration with the MongoDB database for the e-commerce application<br>- By providing essential connection details and a secret key, it ensures secure communication and data management within the backend architecture, supporting the overall functionality and performance of the project.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/config/keys.js'>keys.js</a></b></td>
							<td style='padding: 8px;'>- Facilitates environment-specific configuration management by dynamically loading the appropriate keys based on the applications runtime environment<br>- In production, sensitive credentials are securely sourced from a dedicated production configuration, while a development configuration is utilized during local testing<br>- This approach enhances security and flexibility, ensuring that the application operates correctly across different environments within the overall project architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/backend/config/keys_prod.js'>keys_prod.js</a></b></td>
							<td style='padding: 8px;'>- Configuration management is streamlined through the export of essential keys for connecting to the MongoDB database and securing authentication processes<br>- By utilizing environment variables, sensitive information is kept secure, ensuring that the application can operate effectively in a production environment<br>- This approach enhances the overall architecture by promoting best practices in security and configuration handling within the backend structure.</td>
						</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<!-- frontend Submodule -->
	<details>
		<summary><b>frontend</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ frontend</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/package-lock.json'>package-lock.json</a></b></td>
					<td style='padding: 8px;'>- Project Summary## OverviewThe <code>frontend/package-lock.json</code> file is a crucial component of the project's architecture, specifically designed to manage and lock the dependencies of the frontend application<br>- This file ensures that the exact versions of the libraries and packages used in the project are consistently installed across different environments, thereby enhancing stability and predictability in the development process.## PurposeThe primary purpose of this file is to provide a detailed snapshot of the dependency tree for the frontend application, including all required packages and their respective versions<br>- By doing so, it helps prevent issues that may arise from version discrepancies, ensuring that all developers and deployment environments are using the same set of dependencies.## UsageIn the context of the overall codebase, this file plays a vital role in maintaining the integrity of the frontend application<br>- It allows developers to easily manage and update dependencies while safeguarding against potential conflicts or breaking changes that could disrupt the applications functionality<br>- This contributes to a smoother development workflow and a more reliable end product.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/package.json'>package.json</a></b></td>
					<td style='padding: 8px;'>- Defines the frontend configuration for a React application, establishing essential dependencies and scripts for development, testing, and production builds<br>- It integrates libraries for state management, routing, and API interactions, while also setting up a proxy for backend communication<br>- This structure supports a robust user interface, enabling seamless interaction with the overall codebase architecture.</td>
				</tr>
			</table>
			<!-- src Submodule -->
			<details>
				<summary><b>src</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ frontend.src</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/App.css'>App.css</a></b></td>
							<td style='padding: 8px;'>- Defines the styling for the main application layout, ensuring a flexible and responsive design<br>- By utilizing a columnar flexbox structure, it facilitates a clean separation of content and navigation, promoting an organized user interface<br>- This approach enhances the overall user experience by maintaining consistent spacing and alignment throughout the application, contributing to a cohesive visual presentation across the entire codebase.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/App.test.js'>App.test.js</a></b></td>
							<td style='padding: 8px;'>- Ensures the core functionality of the application by validating that the main component renders correctly<br>- This test checks for the presence of a specific link, confirming that users can access essential features<br>- By integrating this test within the broader project architecture, it enhances reliability and supports ongoing development efforts, fostering a robust user experience in the React application.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/setupTests.js'>setupTests.js</a></b></td>
							<td style='padding: 8px;'>- Enhances testing capabilities by integrating custom Jest matchers specifically designed for DOM node assertions<br>- This setup facilitates more intuitive and expressive testing of React components within the frontend architecture, ensuring that elements behave as expected<br>- By leveraging these matchers, developers can write clearer tests that improve code reliability and maintainability throughout the project.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/index.js'>index.js</a></b></td>
							<td style='padding: 8px;'>- Initializes the React application by rendering the main App component within a structured environment that includes state management through Redux and routing capabilities via React Router<br>- This setup ensures a robust foundation for building a dynamic user interface, while also enabling offline functionality through service workers, ultimately enhancing the overall user experience within the project’s architecture.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/Private-route.jsx'>Private-route.jsx</a></b></td>
							<td style='padding: 8px;'>- Facilitates secure navigation within the application by implementing a private route component that restricts access based on user authentication status<br>- When a user is authenticated, they can access the specified component; otherwise, they are redirected to the sign-in page<br>- This functionality enhances user experience and ensures that sensitive areas of the application remain protected from unauthorized access.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/index.css'>index.css</a></b></td>
							<td style='padding: 8px;'>- Establishes foundational styles for the frontend of the project, ensuring a consistent and visually appealing user interface<br>- By resetting default margins and paddings, it enhances layout control while setting a base font size and typography that promotes readability<br>- This contributes to a cohesive design language across the application, aligning with the overall architecture aimed at delivering a polished user experience.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/App.js'>App.js</a></b></td>
							<td style='padding: 8px;'>- Facilitates the core user interface of the application by integrating essential components such as navigation, footer, and various pages<br>- It manages user authentication by decoding JWT tokens and dispatching user data to the Redux store<br>- The routing structure allows seamless navigation between the home, shop, sign-in, and checkout pages, ensuring a cohesive user experience while protecting sensitive routes with private access.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/serviceWorker.js'>serviceWorker.js</a></b></td>
							<td style='padding: 8px;'>- Service worker registration enhances the applications performance by enabling faster loading on subsequent visits and providing offline capabilities<br>- It ensures that users receive updates only after all existing tabs are closed, thereby managing cached resources effectively<br>- This functionality is crucial for delivering a seamless user experience in production environments, particularly for Progressive Web Apps.</td>
						</tr>
					</table>
					<!-- redux Submodule -->
					<details>
						<summary><b>redux</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ frontend.src.redux</b></code>
							<table style='width: 100%; border-collapse: collapse;'>
							<thead>
								<tr style='background-color: #f8f9fa;'>
									<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
									<th style='text-align: left; padding: 8px;'>Summary</th>
								</tr>
							</thead>
								<tr style='border-bottom: 1px solid #eee;'>
									<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/store.js'>store.js</a></b></td>
									<td style='padding: 8px;'>- Establishes a centralized Redux store for managing application state in the frontend architecture<br>- By integrating middleware such as thunk for asynchronous actions and logger for debugging, it enhances the overall state management process<br>- Additionally, it supports Redux DevTools for improved development experience, ensuring a robust and maintainable codebase that facilitates efficient data flow and state updates across the application.</td>
								</tr>
								<tr style='border-bottom: 1px solid #eee;'>
									<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/root-reducer.js'>root-reducer.js</a></b></td>
									<td style='padding: 8px;'>- Combines multiple reducers into a single root reducer for the Redux store, facilitating state management across the application<br>- By integrating product, cart, and user reducers, it streamlines the handling of application state, ensuring a cohesive and organized architecture that enhances the overall functionality and maintainability of the frontend codebase.</td>
								</tr>
							</table>
							<!-- user Submodule -->
							<details>
								<summary><b>user</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.redux.user</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/user/user.actions.js'>user.actions.js</a></b></td>
											<td style='padding: 8px;'>- User actions facilitate user authentication and management within the application<br>- They enable user registration, login, and logout processes, while also managing the current users state in the Redux store<br>- By handling API interactions and updating local storage, these actions ensure a seamless user experience and maintain session integrity throughout the application.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/user/user.types.js'>user.types.js</a></b></td>
											<td style='padding: 8px;'>- Defines user action types for managing user state within the Redux architecture of the application<br>- By establishing a clear set of constants, it facilitates consistent handling of user-related actions, such as setting the current user<br>- This contributes to a more organized and maintainable codebase, ensuring that user state management is both efficient and predictable across the frontend application.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/user/user.reducer.js'>user.reducer.js</a></b></td>
											<td style='padding: 8px;'>- Manages user state within the Redux architecture of the application, specifically handling the current users information<br>- By defining an initial state and responding to user-related actions, it ensures that the application can dynamically update and maintain user data throughout the user interface<br>- This functionality is crucial for enabling personalized experiences and managing user sessions effectively.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/user/user.selector.js'>user.selector.js</a></b></td>
											<td style='padding: 8px;'>- Facilitates the retrieval of the current user from the application state within the Redux architecture<br>- By leveraging the reselect library, it optimizes state selection, ensuring efficient updates and re-renders in the user interface<br>- This selector plays a crucial role in managing user-related data, enhancing the overall user experience in the frontend application.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- producs Submodule -->
							<details>
								<summary><b>producs</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.redux.producs</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/producs/products.actionTypes.js'>products.actionTypes.js</a></b></td>
											<td style='padding: 8px;'>- Defines action types for product-related operations within the Redux architecture of the frontend application<br>- By establishing a clear set of constants, it facilitates consistent handling of product data retrieval actions across the codebase, ensuring that components can effectively communicate with the Redux store<br>- This structure enhances maintainability and scalability as the application grows.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/producs/products.reducer.js'>products.reducer.js</a></b></td>
											<td style='padding: 8px;'>- Manages the state of product data within the Redux architecture of the frontend application<br>- By handling actions related to product retrieval, it ensures that the application maintains an up-to-date representation of products<br>- This reducer plays a crucial role in enabling seamless interactions and updates in the user interface, contributing to a responsive and dynamic user experience.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/producs/products.action.js'>products.action.js</a></b></td>
											<td style='padding: 8px;'>- Facilitates the retrieval of products based on category by making an API call to the backend<br>- Upon receiving the product data, it dispatches an action to update the Redux store, ensuring that the application state reflects the latest product information<br>- This functionality is essential for maintaining a dynamic and responsive user interface within the overall project architecture.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- cart Submodule -->
							<details>
								<summary><b>cart</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.redux.cart</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/cart/cart.selectors.js'>cart.selectors.js</a></b></td>
											<td style='padding: 8px;'>- Facilitates the calculation of cart-related metrics within the application, enhancing the user experience by providing essential data about cart items<br>- It computes the total number of items and the overall price of the cart, enabling efficient management of shopping cart functionalities<br>- This contributes to a seamless checkout process and supports the overall architecture of the frontend by integrating with the Redux state management system.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/cart/cart.reducer.js'>cart.reducer.js</a></b></td>
											<td style='padding: 8px;'>- Manages the state of the shopping cart within the application, facilitating user interactions by toggling visibility and handling item additions, removals, and clearances<br>- It ensures a seamless shopping experience by maintaining an updated list of cart items and their visibility status, thereby integrating smoothly with the overall architecture of the frontends Redux state management.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/cart/cart.types.js'>cart.types.js</a></b></td>
											<td style='padding: 8px;'>- Defines action types for managing the shopping cart state within the Redux architecture of the frontend application<br>- These action types facilitate user interactions by enabling functionalities such as toggling the cart visibility, adding items, clearing specific items, and removing items from the cart<br>- This structure enhances the overall user experience by ensuring a consistent and efficient state management approach across the application.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/cart/cart.action.js'>cart.action.js</a></b></td>
											<td style='padding: 8px;'>- Cart action creators manage the state of the shopping cart within the application<br>- They facilitate user interactions by toggling the visibility of the cart, adding items, removing items, and clearing specific items from the cart<br>- This functionality is essential for providing a seamless shopping experience, allowing users to efficiently manage their selected products throughout the purchasing process.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/redux/cart/cart.utils.js'>cart.utils.js</a></b></td>
											<td style='padding: 8px;'>- Enhancing cart functionality within the project, the utility functions manage the addition and removal of items in the shopping cart<br>- By updating item quantities or removing items entirely, these functions ensure a seamless user experience during the shopping process<br>- This contributes to the overall architecture by maintaining an accurate representation of the carts state, essential for effective order management and user interactions.</td>
										</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
					<!-- pages Submodule -->
					<details>
						<summary><b>pages</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ frontend.src.pages</b></code>
							<!-- homePage Submodule -->
							<details>
								<summary><b>homePage</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.pages.homePage</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/pages/homePage/homePage.jsx'>homePage.jsx</a></b></td>
											<td style='padding: 8px;'>- Facilitates the rendering of the home page within the application by integrating the Directory component<br>- This structure allows users to navigate through various sections of the app seamlessly, enhancing the overall user experience<br>- Positioned within the frontend architecture, it plays a crucial role in presenting the initial interface and guiding users to explore the available features effectively.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- checkout Submodule -->
							<details>
								<summary><b>checkout</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.pages.checkout</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/pages/checkout/checkout.styles.scss'>checkout.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the checkout page within the frontend architecture, ensuring a user-friendly and visually appealing interface<br>- It establishes layout properties, including dimensions and alignment, while also organizing header elements and total price display<br>- This contributes to a cohesive shopping experience, enhancing usability and guiding users through the checkout process effectively.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/pages/checkout/checkout.component.jsx'>checkout.component.jsx</a></b></td>
											<td style='padding: 8px;'>- CheckoutPage component serves as the user interface for the checkout process in the application, displaying a summary of items in the cart along with their details such as product name, description, quantity, and price<br>- It calculates and presents the total cost of the items, integrating seamlessly with the Redux store to manage cart state, thereby enhancing the overall shopping experience for users.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- shopPage Submodule -->
							<details>
								<summary><b>shopPage</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.pages.shopPage</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/pages/shopPage/shopPage.scss'>shopPage.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the shop page within the frontend architecture, establishing a responsive grid layout that enhances user experience<br>- By allocating space effectively between components, it ensures a visually appealing and organized presentation of products<br>- This contributes to the overall aesthetic and functionality of the application, facilitating seamless navigation and interaction for users exploring the shop.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/pages/shopPage/shopPage.jsx'>shopPage.jsx</a></b></td>
											<td style='padding: 8px;'>- Facilitates the rendering of the shop page within the application, serving as a central hub for displaying categories and items<br>- It integrates category and shop item components, enabling users to navigate through different product categories<br>- The routing functionality allows for dynamic content loading based on selected categories, enhancing the overall shopping experience while maintaining a clean and organized structure within the frontend architecture.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- sign-in-and-sign-up Submodule -->
							<details>
								<summary><b>sign-in-and-sign-up</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.pages.sign-in-and-sign-up</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/pages/sign-in-and-sign-up/sign-in-and-sign-up.component.jsx'>sign-in-and-sign-up.component.jsx</a></b></td>
											<td style='padding: 8px;'>- Facilitates user authentication by combining sign-in and sign-up functionalities within a single page<br>- This component serves as a central hub for user access management, enhancing the overall user experience by providing seamless navigation between signing in and creating a new account<br>- It integrates dedicated components for both processes, ensuring a cohesive and intuitive interface for users.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/pages/sign-in-and-sign-up/sign-in-and-sign-up.styles.scss'>sign-in-and-sign-up.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the sign-in and sign-up page, establishing a visually appealing and user-friendly layout<br>- By setting dimensions and alignment properties, it ensures that the components are well-organized and accessible, contributing to an overall cohesive user experience within the frontend architecture of the project<br>- This enhances usability and encourages user engagement during the authentication process.</td>
										</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
					<!-- components Submodule -->
					<details>
						<summary><b>components</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ frontend.src.components</b></code>
							<!-- form-input Submodule -->
							<details>
								<summary><b>form-input</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.form-input</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/form-input/form-input.component.jsx'>form-input.component.jsx</a></b></td>
											<td style='padding: 8px;'>- Provides a reusable form input component that enhances user interaction within the frontend architecture<br>- It integrates a label that dynamically adjusts based on user input, ensuring a clear and engaging experience<br>- This component streamlines form handling by encapsulating input behavior and styling, contributing to a cohesive and maintainable user interface across the application.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/form-input/form-input.styles.scss'>form-input.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines styling for form input components, enhancing user experience through visually appealing and functional design<br>- It establishes a cohesive look with color schemes and responsive label behavior, ensuring clarity during user interaction<br>- By incorporating transitions and focus states, it contributes to a polished interface that aligns with the overall architecture of the frontend, promoting usability and aesthetic consistency across the application.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- category Submodule -->
							<details>
								<summary><b>category</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.category</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/category/category.component.jsx'>category.component.jsx</a></b></td>
											<td style='padding: 8px;'>- CategoryItem component serves as a dynamic interface for displaying product categories within the application<br>- It enables users to navigate to specific category pages, triggering the retrieval of relevant products through a Redux action<br>- By integrating with the routing system, it enhances user experience and facilitates seamless access to the shops offerings, contributing to the overall architecture of the frontend by promoting organized and efficient category management.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/category/cat_data.js'>cat_data.js</a></b></td>
											<td style='padding: 8px;'>- Defines a constant array of category names that represent different segments of a product catalog within the frontend application<br>- This categorization enhances the user experience by allowing for organized navigation and filtering of products, contributing to a structured and intuitive interface<br>- The integration of these category names supports the overall architecture by facilitating seamless interactions between components and the underlying data.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/category/category.styles.scss'>category.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the category component within the frontend architecture, establishing a structured and visually appealing layout<br>- It enhances user interaction through hover and focus effects on links, ensuring a consistent and engaging experience<br>- This contributes to the overall aesthetic and usability of the application, aligning with the projects goal of delivering a seamless user interface.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- directory-item Submodule -->
							<details>
								<summary><b>directory-item</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.directory-item</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/directory-item/directoryItem.component.jsx'>directoryItem.component.jsx</a></b></td>
											<td style='padding: 8px;'>- DirectoryItem serves as a visual and interactive component within the frontend architecture, enabling users to navigate through different sections of the application<br>- By displaying an image and title, it enhances user engagement and facilitates seamless routing to specific content areas<br>- This component plays a crucial role in organizing the user interface, contributing to a cohesive and intuitive browsing experience.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/directory-item/directoryItem.styles.scss'>directoryItem.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for directory items within the frontend component architecture, ensuring a visually appealing and user-friendly interface<br>- It establishes layout properties, dimensions, and hover effects, enhancing the overall user experience<br>- The design promotes a cohesive look and feel across the application, contributing to the projects goal of delivering an intuitive and engaging platform for users to navigate through various directories.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- shop-item-card Submodule -->
							<details>
								<summary><b>shop-item-card</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.shop-item-card</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/shop-item-card/shopItemCard.component.jsx'>shopItemCard.component.jsx</a></b></td>
											<td style='padding: 8px;'>- ShopItemCard serves as a visual component within the e-commerce platform, showcasing individual items for sale<br>- It displays essential product details such as the name, image, and price, while providing an interactive button to add items to the shopping cart<br>- By integrating with Redux, it facilitates seamless state management for cart operations, enhancing the overall user experience in the shopping process.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/shop-item-card/shopItemCard.styles.scss'>shopItemCard.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for shop item cards within the frontend component architecture, enhancing the visual presentation and user interaction<br>- It establishes a responsive layout that showcases product images, details, and pricing, while incorporating hover effects to improve engagement<br>- This contributes to a cohesive and appealing shopping experience, aligning with the overall design principles of the application.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- checkout-item Submodule -->
							<details>
								<summary><b>checkout-item</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.checkout-item</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/checkout-item/checkout-item.styles.scss'>checkout-item.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the checkout item component within the frontend architecture, ensuring a visually appealing and user-friendly interface<br>- It establishes layout properties, including dimensions and alignment, for elements such as images, product names, quantities, prices, and interactive buttons<br>- This enhances the overall shopping experience by providing clear organization and accessibility in the checkout process.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/checkout-item/checkout-item.component.jsx'>checkout-item.component.jsx</a></b></td>
											<td style='padding: 8px;'>- CheckoutItem component facilitates the display and management of individual items within the shopping cart<br>- It allows users to view item details, adjust quantities, and remove items from the cart<br>- By integrating with Redux, it ensures that any changes made to the cart are reflected in the global state, enhancing the overall user experience during the checkout process.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- shop-items Submodule -->
							<details>
								<summary><b>shop-items</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.shop-items</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/shop-items/shop-items.component.jsx'>shop-items.component.jsx</a></b></td>
											<td style='padding: 8px;'>- Facilitates the display of shop items within the application by rendering a collection of product cards<br>- It connects to the Redux store to retrieve product data, ensuring that the latest items are presented to users<br>- This component plays a crucial role in the overall architecture by integrating state management with the user interface, enhancing the shopping experience.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/shop-items/shop.data.js.js'>shop.data.js.js</a></b></td>
											<td style='padding: 8px;'>- SHOP_DATA serves as a centralized repository of product information for an e-commerce platform, categorizing items into distinct sections such as Hats, Sneakers, Jackets, Womens, and Mens<br>- Each category includes relevant details like product names, images, and prices, facilitating seamless integration with the frontend components<br>- This structured data enhances user experience by enabling efficient browsing and purchasing of merchandise within the application.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/shop-items/shop-items.styles.scss'>shop-items.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the product display section within the shop component of the frontend application<br>- By utilizing a grid layout, it ensures a responsive and visually appealing arrangement of products, adapting to various screen sizes<br>- This enhances user experience by promoting easy navigation and interaction with the shop items, contributing to the overall aesthetic and functionality of the e-commerce platform.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- navLinks Submodule -->
							<details>
								<summary><b>navLinks</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.navLinks</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/navLinks/navLink.component.jsx'>navLink.component.jsx</a></b></td>
											<td style='padding: 8px;'>- Facilitates navigation within the application by rendering dynamic link components that adapt based on user context and application state<br>- Enhances user experience by providing intuitive access to various sections of the platform, ensuring seamless interaction and engagement<br>- Positioned within the frontend architecture, it plays a crucial role in maintaining a cohesive and user-friendly interface throughout the application.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- cart-icon Submodule -->
							<details>
								<summary><b>cart-icon</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.cart-icon</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/cart-icon/cart-icon.component.jsx'>cart-icon.component.jsx</a></b></td>
											<td style='padding: 8px;'>- CartIcon component serves as a visual representation of the shopping cart within the application, allowing users to easily access their cart<br>- It displays the number of items currently in the cart and toggles the visibility of the cart when clicked<br>- By integrating with Redux, it efficiently retrieves the cart item count from the global state, enhancing the user experience in the e-commerce platform.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/cart-icon/cart-icon.styles.scss'>cart-icon.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the cart icon component within the frontend architecture, enhancing user interaction and visual appeal<br>- By establishing dimensions, positioning, and layout, it ensures a cohesive design that integrates seamlessly with the overall user interface<br>- The component also incorporates an item count display, providing users with immediate feedback on their shopping cart status, thereby improving the shopping experience.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- stripe-button Submodule -->
							<details>
								<summary><b>stripe-button</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.stripe-button</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/stripe-button/stripe-button.styles.scss'>stripe-button.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the Stripe button component within the frontend architecture, enhancing the user interface and experience during payment processing<br>- By establishing a cohesive visual design, it ensures that the payment functionality aligns with the overall aesthetic of the application, contributing to a seamless and engaging user journey throughout the checkout process.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/stripe-button/stripe-button.component.jsx'>stripe-button.component.jsx</a></b></td>
											<td style='padding: 8px;'>- Facilitates seamless payment processing within the application by integrating Stripes checkout functionality<br>- It allows users to make payments for their purchases, enhancing the e-commerce experience<br>- By capturing payment details and confirming successful transactions, it plays a crucial role in the overall architecture, ensuring secure and efficient financial interactions for users of the Crown Clothing LTD<br>- platform.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- cart-dropdown Submodule -->
							<details>
								<summary><b>cart-dropdown</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.cart-dropdown</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/cart-dropdown/cart-dropdown.component.jsx'>cart-dropdown.component.jsx</a></b></td>
											<td style='padding: 8px;'>- CartDropdown serves as a user interface component that displays the items currently in the shopping cart<br>- It dynamically renders each cart item and provides a button for users to proceed to the checkout page<br>- By connecting to the Redux store, it retrieves the cart items, ensuring a seamless integration with the overall application architecture, enhancing the shopping experience for users.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/cart-dropdown/cart-dropdown.styles.scss'>cart-dropdown.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the cart dropdown component within the frontend architecture, enhancing user experience by providing a visually appealing and functional interface<br>- It establishes layout properties, such as positioning and dimensions, while ensuring a clear presentation of cart items and an empty message<br>- This contributes to the overall usability of the shopping experience in the application.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- sign-up Submodule -->
							<details>
								<summary><b>sign-up</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.sign-up</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/sign-up/sign-up.component.jsx'>sign-up.component.jsx</a></b></td>
											<td style='padding: 8px;'>- SignUp component facilitates user registration by providing a form for inputting display name, email, password, and password confirmation<br>- It validates the password match and dispatches a registration action to the Redux store upon submission<br>- This component plays a crucial role in the user authentication flow within the application, enhancing user experience by enabling account creation seamlessly.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/sign-up/sign-up.styles.scss'>sign-up.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the sign-up component within the frontend architecture, ensuring a user-friendly layout<br>- By utilizing a flexible column structure, it enhances the visual appeal and usability of the sign-up form<br>- The design elements, such as margins for the title, contribute to a cohesive and engaging user experience, aligning with the overall aesthetic of the application.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- footer Submodule -->
							<details>
								<summary><b>footer</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.footer</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/footer/footer.component.jsx'>footer.component.jsx</a></b></td>
											<td style='padding: 8px;'>- Provides a footer component for the application, enhancing the user interface by displaying copyright information and crediting the designer<br>- Positioned within the frontend structure, this component contributes to the overall aesthetic and functionality of the project, ensuring a polished and professional appearance while maintaining brand identity through linked attribution.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/footer/footer.styles.scss'>footer.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the footer component within the frontend architecture, ensuring a visually appealing and cohesive design<br>- By setting properties such as font size, background color, and layout, it enhances user experience and accessibility<br>- This contributes to the overall aesthetic and functionality of the application, aligning with the projects goal of delivering a polished and user-friendly interface.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- navigation Submodule -->
							<details>
								<summary><b>navigation</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.navigation</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/navigation/mainNavigation.styles.scss'>mainNavigation.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the main navigation header within the frontend component architecture<br>- It establishes a visually appealing layout that enhances user experience by ensuring a responsive and organized navigation structure<br>- The design emphasizes flexibility and alignment, facilitating easy access to key navigation links while maintaining a cohesive aesthetic across the application.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/navigation/mainNavigation.component.jsx'>mainNavigation.component.jsx</a></b></td>
											<td style='padding: 8px;'>- MainNavigation component serves as the primary navigation interface for the application, enabling users to seamlessly access different sections such as the shop and sign-in/sign-up options<br>- It dynamically reflects the users authentication status, allowing for logout functionality when a user is logged in<br>- Additionally, it incorporates a cart icon that toggles the visibility of the cart dropdown, enhancing the overall user experience within the e-commerce platform.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- sign-in Submodule -->
							<details>
								<summary><b>sign-in</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.sign-in</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/sign-in/sign-in.styles.scss'>sign-in.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the sign-in component within the frontend architecture, ensuring a user-friendly interface<br>- By establishing layout properties such as width and flexbox arrangements, it enhances the visual organization of elements like titles and buttons<br>- This contributes to a cohesive user experience, aligning with the overall design principles of the application.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/sign-in/sign-in.component.jsx'>sign-in.component.jsx</a></b></td>
											<td style='padding: 8px;'>- SignIn component facilitates user authentication by providing a user interface for email and password input<br>- It integrates with Redux to manage login actions and utilizes React Router for navigation<br>- By allowing users to sign in with their credentials or through Google, it enhances the overall user experience within the application, ensuring secure access to personalized features and content.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- cart-item Submodule -->
							<details>
								<summary><b>cart-item</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.cart-item</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/cart-item/cart-item.component.jsx'>cart-item.component.jsx</a></b></td>
											<td style='padding: 8px;'>- Displays individual cart items within the shopping cart interface, showcasing essential details such as the items image, name, price, and quantity<br>- This component enhances the user experience by providing a clear and organized view of selected products, contributing to the overall functionality of the e-commerce platforms frontend architecture<br>- Its integration supports seamless interaction and visual appeal in the cart management system.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/cart-item/cart-item.styles.scss'>cart-item.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for cart items within the frontend component architecture, ensuring a cohesive and visually appealing layout<br>- By establishing a flexible structure, it enhances user experience through organized item presentation, including image and detail alignment<br>- This contributes to the overall aesthetic and functionality of the shopping cart interface, facilitating seamless interaction for users.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- directory Submodule -->
							<details>
								<summary><b>directory</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.directory</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/directory/directory-data.js'>directory-data.js</a></b></td>
											<td style='padding: 8px;'>- Defines a structured collection of product categories for an e-commerce platform, including hats, jackets, sneakers, and apparel for both women and men<br>- Each category is associated with an image and a link for easy navigation, enhancing the user experience by facilitating access to various product sections<br>- This component plays a crucial role in the overall architecture by organizing and presenting key offerings to users.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/directory/directory.component.jsx'>directory.component.jsx</a></b></td>
											<td style='padding: 8px;'>- Facilitates the rendering of a directory component within the frontend architecture, showcasing a collection of items sourced from predefined data<br>- By mapping through the directory sections, it dynamically generates individual directory items, enhancing user interaction and navigation<br>- This component plays a crucial role in organizing content visually, contributing to the overall user experience of the application.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/directory/directory.styles.scss'>directory.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for the directory component within the frontend architecture, ensuring a responsive layout that adapts to various screen sizes<br>- By utilizing flexbox properties, it facilitates a visually appealing arrangement of items, enhancing user experience through effective spacing and padding<br>- This contributes to the overall aesthetic and functional coherence of the application’s user interface.</td>
										</tr>
									</table>
								</blockquote>
							</details>
							<!-- custom-button Submodule -->
							<details>
								<summary><b>custom-button</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ frontend.src.components.custom-button</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/custom-button/custom-button.styles.scss'>custom-button.styles.scss</a></b></td>
											<td style='padding: 8px;'>- Defines the styling for custom buttons within the frontend component architecture, ensuring a consistent and visually appealing user interface<br>- It establishes various states for the buttons, including hover effects and specific styles for Google sign-in and inverted variants<br>- This enhances user interaction and accessibility, contributing to a cohesive design language across the application.</td>
										</tr>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/src/components/custom-button/custom-button.component.jsx'>custom-button.component.jsx</a></b></td>
											<td style='padding: 8px;'>- CustomButton serves as a versatile UI component within the project, designed to enhance user interaction by providing a styled button element<br>- It accommodates various use cases, such as Google sign-in and inverted styles, while allowing for additional properties to be passed through<br>- This component contributes to a cohesive and customizable user interface, aligning with the overall architectures focus on modular and reusable design elements.</td>
										</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<!-- public Submodule -->
			<details>
				<summary><b>public</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ frontend.public</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/public/index.html'>index.html</a></b></td>
							<td style='padding: 8px;'>- Defines the foundational structure for the web application, serving as the entry point for users<br>- It establishes essential metadata, links to stylesheets, and integrates a manifest for progressive web app capabilities<br>- By facilitating client-side routing and ensuring compatibility with various environments, it enhances the overall user experience for the Ecommerce-Shop project, enabling seamless navigation and interaction within the application.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/public/robots.txt'>robots.txt</a></b></td>
							<td style='padding: 8px;'>- Facilitates web crawling by providing directives for search engine bots<br>- The robots.txt located in the frontend/public directory allows all user agents to access the site without restrictions, ensuring optimal visibility and indexing by search engines<br>- This contributes to the overall architecture by enhancing discoverability and improving the projects online presence.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/maximusmenendez/Ecommerce-App/blob/master/frontend/public/manifest.json'>manifest.json</a></b></td>
							<td style='padding: 8px;'>- Defines the web apps manifest, providing essential metadata for the Create React App Sample project<br>- It specifies the apps name, icons, and display settings, ensuring a cohesive user experience across devices<br>- By establishing the theme and background colors, it enhances the visual identity, while the start URL facilitates seamless navigation, contributing to the overall architecture of a progressive web application.</td>
						</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
</details>

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** JavaScript
- **Package Manager:** Npm

### Installation

Build Ecommerce-App from the source and intsall dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/maximusmenendez/Ecommerce-App
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Ecommerce-App
    ```

3. **Install the dependencies:**

**Using [npm](https://www.npmjs.com/):**

```sh
❯ npm install
```

### Usage

Run the project with:

**Using [npm](https://www.npmjs.com/):**

```sh
npm start
```

### Testing

Ecommerce-app uses the {__test_framework__} test framework. Run the test suite with:

**Using [npm](https://www.npmjs.com/):**

```sh
npm test
```

---

## Roadmap

- [X] **`Task 1`**: <strike>Implement feature one.</strike>
- [ ] **`Task 2`**: Implement feature two.
- [ ] **`Task 3`**: Implement feature three.

---

## Contributing

- **💬 [Join the Discussions](https://github.com/maximusmenendez/Ecommerce-App/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/maximusmenendez/Ecommerce-App/issues)**: Submit bugs found or log feature requests for the `Ecommerce-App` project.
- **💡 [Submit Pull Requests](https://github.com/maximusmenendez/Ecommerce-App/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/maximusmenendez/Ecommerce-App
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/maximusmenendez/Ecommerce-App/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=maximusmenendez/Ecommerce-App">
   </a>
</p>
</details>

---

## License

Ecommerce-app is protected under the [LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## Acknowledgments

- Credit `contributors`, `inspiration`, `references`, etc.

<div align="left"><a href="#top">⬆ Return</a></div>

---
