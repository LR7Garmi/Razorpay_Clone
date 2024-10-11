# Razorpay Navbar

This project is a frontend implementation for Razorpay's navigation bar. It aims to provide a seamless and intuitive user experience for navigating through various sections of the Razorpay platform.

## Features

- Responsive design
- Easy integration
- Customizable components

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/razorpay-navbar.git
cd razorpay-navbar
npm install
```

## Usage

To run the project locally, use the following command:

1. Clone this repository

2. build css configurations using following commands:
    ```bash
    npm install tailwindcss postcss autoprefixer
    ```
3. Add the follwing text to your style.css file
    ```bash
    @tailwind base;
    @tailwind components;
    @tailwind utilities;    
    ```

4. Build output.css file using this style.css file

  ```bash
  npx tailwindcss -i ./style.css -o ./output.css --watch
  ```

5. link the output.css file in yout index.html file

6. Make sure that your tailwind.config.js file exists

```bash
npm start
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.