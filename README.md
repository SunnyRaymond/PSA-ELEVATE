# PSA Elevate - Frontend

**PSA Elevate** is a frontend platform that provides a user-friendly dashboard for employees to track their learning progress, submit their CVs, and get course and mentor recommendations. This project is part of a hackathon focused on building innovative, AI-driven solutions for workforce development.

## Features

- **User Authentication**: Users can log in using their credentials and access personalized features.
- **Dashboard**: Displays user details, completed courses, and job description.
- **CV Submission**: Users can upload their CVs to the platform.
- **Recommended Courses**: Personalized course recommendations based on user profile.
- **Recommended Mentors**: Mentors suggested based on skills gaps identified in the user's job description and CV.
- **Loading Overlay**: When submitting CVs, the platform displays a loading overlay for a smoother user experience.

## Technologies Used

- **React**: Front-end framework used for building the user interface.
- **JavaScript (ES6+)**: Language used for logic and interactivity.
- **Fetch API**: Used to handle API requests to the backend.
- **Bootstrap**: For responsive and modern styling.
- **CSS**: Custom styles for components.
- **GitHub**: Version control and project collaboration.

## Installation

To run the project locally, follow these steps:

### Prerequisites

- **Node.js** (version 14+)
- **npm** or **yarn** installed globally

### Step-by-Step Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/psa-elevate-frontend.git
   cd psa-elevate-frontend
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```
   or if using Yarn:
   ```bash
   yarn install
   ```

3. **Start the Development Server**
   ```bash
   npm start
   ```
   or if using Yarn:
   ```bash
   yarn start
   ```

4. **Open the Application**
   Once the server is running, navigate to `http://localhost:3000` in your web browser.

### API Endpoints

- **Login**: The login request sends the username and password to the backend for authentication.
  - Endpoint: `http://20b97877.r6.cpolar.cn/api/login/`
  - Request Body: `{"username":"example_user","password":"example_password"}`
  
- **Upload CV**: Users can upload their CV as a PDF.
  - Endpoint: `http://20b97877.r6.cpolar.cn/api/upload-cv/`
  - Request Body: FormData object containing the username and CV file.

### Project Structure

```
├── public/                 # Static files
├── src/                    # Main source files
│   ├── components/         # Reusable components
│   ├── styles/             # Custom CSS files for styling
│   ├── App.js              # Main App component
│   ├── Dashboard.js        # Main Dashboard component
│   └── index.js            # Application entry point
├── README.md               # Project documentation
├── package.json            # Project dependencies and scripts
└── .gitignore              # Files to ignore in Git
```

## Contributing

We welcome contributions! Please follow the steps below:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add your feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.

## License

This project is licensed under the MIT License.
