
# GraphQL Profile Page

## Description

This project is a personal profile page built using the GraphQL query language. The profile page dynamically displays user-specific data retrieved from a GraphQL endpoint. It also features an interactive UI with statistical graphs generated using SVG.

## Features

- **User Profile Display**: Shows key user information such as identification, XP, grades, and audit ratios.
- **Statistical Graphs**: Generates interactive and animated graphs using SVG to visualise various metrics like XP progression, project pass/fail ratios, and more.
- **JWT Authentication**: Secured login system using JWT, allowing users to authenticate via their 01-Founders credentials.
- **Responsive UI**: A user-friendly interface designed with good UI/UX principles in mind.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://learn.01founders.co/git/jsmith/graphql.git
   cd graphql
   ```

2. **Environment Setup**:
   - In the root directory of the project, create a new file named `.env`.
   - Open the `.env` file in your text editor and add the following environment variables:

     ```env
     GRAPHQL_ENDPOINT=https://learn.01founders.co/api/graphql-engine/v1/graphql
     ```

   - Save the `.env` file.

3. **Run the Project**:
   - Open the project folder in your code editor.
   - Right-click on the `index.html` file.
   - Select "Open with Live Server" (this requires the Live Server extension in your code editor).

## Usage

1. **Login**:
   - Log in using your 01-Founders credentials.

2. **Explore Your Profile**:
   - Once logged in, explore the profile page to view your data and interact with the statistical graphs.

## Technologies Used

- **GraphQL**
- **HTML/CSS**
- **SVG for Graphs**
- **JWT for Authentication**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
