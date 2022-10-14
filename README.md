



<!-- PROJECT SHIELDS -->




<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">React Social Media - RadSocial</h3>

  <p align="center">
    A facebook clone created using the MERN stack.
    <br />
    <br />
    ·
    <a href="https://github.com/genius-ayush/social-media-application/issues">Report Bug</a>
    
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]]

I wanted to use the react fundamentals that I have learned from my react pokedex project (hosted on my github), as well as the fullstack fundamentals that I learned from creating my campgrounds viewing web application (hosted on github as well), to create a fullstack social media platform site. I will add more features as I learn more about web development, and hopefully others can learn from this project as well.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
* ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
* ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
* ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

1. First perform ```git clone <githuburl>``` to get all source files locally
2. Install nodemodules ```npm install``` in root folder
3. Create a local build of client by executing ```npm run local``` in root folder
4. Start the local server by executing ```npm start``` in root folder
5. include .env file in root folder with following credentials

CLOUDINARY_NAME='enter cloudinary api name'
CLOUDINARY_API_KEY='enter cloudinary api key'
CLOUDINARY_API_SECRET='enter cloudinary api secret'
SESSION_SECRET='write a secret, it can be a random string eg: helloworld'
MONGO_URL='enter mongoatlas url, starts with mongodb://'

<!-- USAGE EXAMPLES -->
## Usage

- You are free to use a test account username:cattleherd password:password for demo purposes.
- Login using the demo account credentials


### To create a post
1. Click the green album icon which will prompt you to upload an image
2. You may also write a description
3. Press the share button to create a post!

[![Product Name Screen Shot][product-screenshot2]]

- The items highlighted are the different interactivity points of the homepage
- The top left allows you to search the profile of any registered user
- The messenger icon below it will give you access to live chat features
- The profile page button will redirect to your profile page

### Adding a friend

- In order to follow someone you must search their profile page using the search icon on the top left, then press the follow button
- The user will only show up on the friends list if they are following you as well (both parties must follow eachother)
- Only friends will show up in Messenger app

[![Product Name Screen Shot][product-screenshot3]]

### Chatting in real-time using messenger app
- Users can select a conversation on the left to view conversations
- the notification circle will turn from gray to green when the friend is online
- messages are sent and received in real-time
- logging out is easy, just click log-out on the top right

[![Product Name Screen Shot][product-screenshot4]]




<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>








