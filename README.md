# Web Simulation of UbuntuOS

This is a personal portfolio website with an Ubuntu 20.04 theme, made using Next.js & Tailwind CSS.
If you want to edit this, clone this project and edit the files in the [`/src/components`](/src/components) directory.

![Ubuntu 20.04 Theme](https://ubuntu.com/blog/wp-content/uploads/5d14/focal-fossa-wallpaper-1.jpg)

> Experience the familiar Ubuntu desktop environment in your browser!

## Getting Started

To run this on localhost:
1. Type `npm start` to start the development server
2. When you're done coding, type `npm run build` to build your app

_NOTE: If you have yarn installed, just replace `npm start` and `npm run build` with `yarn start` and `yarn build`._

## Setting Up the Contact Form

To make the contact form work:

1. Create an account in [EmailJS](https://www.emailjs.com/) and also create a new Outlook or Gmail account to be able
   to send emails
2. Create a new service in EmailJS, then select and log in to your newly created Outlook or Gmail account
3. Go back to the dashboard and copy your Service ID
4. Create a `.env` file in your root folder and add the following:

```env
NEXT_PUBLIC_USER_ID = 'YOUR_USER_ID'
NEXT_PUBLIC_TEMPLATE_ID = 'template_fqqqb9g'
NEXT_PUBLIC_SERVICE_ID = 'YOUR_SERVICE_ID'
```

Replace `YOUR_USER_ID` and `YOUR_SERVICE_ID` with your actual values from your EmailJS service.

## Available Scripts

This project was made using Create Next App. Here are the scripts that you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run build && npm run export`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributors who want to make this website better can make contributions, which will be **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Added some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
