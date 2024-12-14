## About The Project

![Screenshot from 2024-12-14 13-41-56](https://github.com/user-attachments/assets/df4d8de6-d99d-4b38-aa01-e90c05d4d3ce)

This project is a simple yet powerful tool for creating a personalized hub for all your social media links. Inspired by platforms like LinkTree, it allows users to centralize their online presence in a single, shareable URL.  

### Key Features

- **Personalized Link Hubs**: Users can create a custom page displaying their social media links.  
- **Customizable URLs**: Generate a unique and shareable URL for your profile, making it easy to share your links with anyone.  
- **Responsive Design**: Ensures an optimized viewing experience across all devices, from mobile to desktop.  
- **User-Friendly Interface**: A simple, intuitive UI for adding, editing, and organizing your links. 

### Built With

This app was designed to be both scalable and user-friendly, offering a modern solution to task and project management.

- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vite.dev/)
- [TailwindCSS](https://tailwindcss.com/)


## Usage

For those interested in how the project works without having to install it, here are some screenshots showcasing its key features:  

*Home Page* 
![Screenshot from 2024-12-14 13-41-56](https://github.com/user-attachments/assets/df4d8de6-d99d-4b38-aa01-e90c05d4d3ce)


*Login / Register pages*  
![Screenshot from 2024-12-14 13-42-05](https://github.com/user-attachments/assets/4d490ca5-682d-4301-8e50-2c8d4d9642ff)


*Update your profile data* 
![Screenshot from 2024-12-14 13-42-40](https://github.com/user-attachments/assets/bf88f909-baca-438f-9cf6-c83e4b2c01cd)


*Manage your socials*  
![Screenshot from 2024-12-14 13-42-24](https://github.com/user-attachments/assets/17665d72-2bd9-4358-92a5-424f98f9253a)
![Screenshot from 2024-12-14 13-44-34](https://github.com/user-attachments/assets/75e05ddf-3c2a-4229-abb1-e13e46787d02)


*Your profile page*  
![Screenshot from 2024-12-14 13-42-47](https://github.com/user-attachments/assets/c34d6833-627a-4f0a-9375-c037901cd8d0)


## Getting Started

Follow the steps below to set up the project locally:

### Prerequisites

To get started first you will need to install the following:

- NodeJS
- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [MongoDB](https://www.mongodb.com/es/cloud/atlas/register)
2. Get a free API Key at [Cloudinary](https://cloudinary.com/users/register_free)
3. Clone the repo
   ```sh
   git clone https://github.com/DaniGarridoNunez/snaplink_backend.git
   ```
4. Install NPM packages in both /frontend and /backend
   ```sh
   npm install
   ```
5. Enter your API keys in `.env` at /backend for example:
   ```sh
    FRONTEND_URL= http://localhost:5173
    MONGO_URI=mongodb+srv://root:<db_password>@cluster0.example.mongodb.net/snaplink
    CLOUDINARY_NAME=name
    CLOUDINARY_API_KEY=apikey
    CLOUDINARY_API_SECRET=apisecret
    JWT_SECRET=palabrasupersecreta
   ```
6. Enter your API keys in `.env.local` at /frontend:
    ```sh
    VITE_API_URL=http://localhost:4000
    ```
7. And then run in both /frontend and /backend:
   ```sh
   npm run dev
   ```


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git switch -c feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [MIT License](https://opensource.org/licenses/MIT) for more information.

## Contact

Daniel Garrido - danigarridonunez@gmail.com - [LinkedIn Profile](https://www.linkedin.com/in/daniel-garrido-87b041223/)
