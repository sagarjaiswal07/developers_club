<!-- PROJECT SHIELDS -->



<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">React Social Media - RadSocial</h3>

  <p align="center">
    A facebook clone created using the MERN stack.
    <br />
    <br />
  <a href="https://github.com/cattleherd/react-social-media/issues">Report Bug</a>
    
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

![Product Name Screen Shot][product-screenshot]

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

1. First perform git clone <githuburl> to get all source files locally
2. Install nodemodules npm install in root folder
3. Create a local build of client by executing npm run local in root folder
4. Start the local server by executing npm start in root folder
5. include .env file in root folder with following credentials

CLOUDINARY_NAME='enter cloudinary api name'</br>
CLOUDINARY_API_KEY='enter cloudinary api key'</br>
CLOUDINARY_API_SECRET='enter cloudinary api secret'</br>
SESSION_SECRET='write a secret, it can be a random string eg: helloworld'</br>
MONGO_URL='enter mongoatlas url, starts with mongodb://'</br>

<!-- USAGE EXAMPLES -->
## Usage

- You are free to use a test account username:cattleherd password:password for demo purposes.
- Login using the demo account credentials


### To create a post
1. Click the green album icon which will prompt you to upload an image
2. You may also write a description
3. Press the share button to create a post!

![Product Name Screen Shot][product-screenshot2]

- The items highlighted are the different interactivity points of the homepage
- The top left allows you to search the profile of any registered user
- The messenger icon below it will give you access to live chat features
- The profile page button will redirect to your profile page

### Adding a friend

- In order to follow someone you must search their profile page using the search icon on the top left, then press the follow button
- The user will only show up on the friends list if they are following you as well (both parties must follow eachother)
- Only friends will show up in Messenger app

![Product Name Screen Shot][product-screenshot3]

### Chatting in real-time using messenger app
- Users can select a conversation on the left to view conversations
- the notification circle will turn from gray to green when the friend is online
- messages are sent and received in real-time
- logging out is easy, just click log-out on the top right

![Product Name Screen Shot][product-screenshot4]




<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are *greatly appreciated*.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: https://res.cloudinary.com/cattleherd/image/upload/v1662760777/react-social-media-github/pic_toaxqf.png
[product-screenshot2]: https://res.cloudinary.com/cattleherd/image/upload/v1662761225/react-social-media-github/pic_srf3ht.png
[product-screenshot3]: https://res.cloudinary.com/cattleherd/image/upload/v1662761648/react-social-media-github/pic_aykgrh.png
[product-screenshot4]: https://res.cloudinary.com/cattleherd/image/upload/v1662762041/react-social-media-github/pic_iqorld.png
[Express.js]: https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB
[NodeJS]: [https://nextjs.org/](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[MongoDB]: https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com
