## React Form with Validation

This project contains a React component called `SignupForm` that allows users to sign up with their email, name, country, age, and password. It implements client-side validation to ensure that the email is in a valid format and the password is at least 8 characters long.

### Features

- Client-side validation for email format and password length.
- Error messages displayed next to each input field if validation fails.
- Submit button disabled until the form is valid.
- Implemented using functional components and React hooks.

### How to Use

1. Clone the repository to your local machine:

```bash
git clone 
```

2. Navigate to the `react-form-validation` directory:

```bash
cd react-form-validation
```

3. Install dependencies:

```bash
npm install
```

4. Run the application:

```bash
npm start
```

5. Access the application in your browser at `http://localhost:3000`.

### Directory Structure

- `src/components/SignupForm.js`: Contains the `SignupForm` component code.
- `src/validationSchema.js`: Contains the validation schema using Yup.
- `src/App.js`: Main component to render the `SignupForm`.
- `public/index.html`: HTML template file.

### Technologies Used

- React: JavaScript library for building user interfaces.
- React Hook Form: Library for managing form state and validation.
- Yup: JavaScript schema builder for validation.
- HTML/CSS: Markup and styling for the form.

### Credits

This project was created by Ritik Singh as part of a programming challenge.

### License

This project is licensed under the [MIT License](LICENSE).