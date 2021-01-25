<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/DanTcheche/your_social_life_bot">
    <img src="media/your_social_life_bot.png" alt="Logo">
  </a>

  <h3 align="center">Your social life bot</h3>

  <p align="center">
    Telegram bot to help you with your social life.
    <br />
    <a href="https://github.com/DanTcheche/your_social_life_bot"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/DanTcheche/your_social_life_bot/issues">Report Bug</a>
    ·
    <a href="https://github.com/DanTcheche/your_social_life_bot/issues">Request Feature</a>
·
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
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
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Why the exponential growth of Telegram in the last month I found myself
interested in building some usefull bots to help in the daily life.

The current main functionalities are:
* Birthdays management.
  * Adding birthdays.
  * Listing birthdays.
  * Getting next birthday.
  * Notification when a it's someones birthday.
    
* Events management.
  * Adding events.
  * Listing next events.
  * Getting next event.
  * Notification the day of an event.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Python](https://www.python.org/)
* [MongoDB](https://www.mongodb.com/)

<!-- GETTING STARTED -->
## Getting Started

Open [@BotFather](https://telegram.me/botfather) on Telegram and create a new bot with the `/newbot` command.

Assign it a name. This name won't be the one that is shown on each message, so you can name it whatever you want.

@BotFather will grant you a Token. This is the TOKEN you'll need to interact with the BOT. Keep it private!

![./media/bot_father.png](media/bot_father.png)

You can also use the `/setcommands` to define the uses your bot has on the '/' icon:

![./media/bot_father_add_commands.png](media/bot_father_add_commands.png)

### Installation

1. Make sure you are running python:
    1. Use [pyenv-installer](https://github.com/pyenv/pyenv-installer) for installing pyenv
    1. See which python versions are available: `pyenv install --list`
    1. Install python 3. Example: `pyenv install 3.6.6` (3.6.6 or higher)
    1. `pyenv shell 3.6.6`

    
2. Install bot dependencies:
   ```sh
   pip3 install python-telegram-bot
   ```
3. Install pymongo:
   ```sh
   pip3 pymongo
   ```
4. Run the app:
   ```JS
   python3 main.py
   ```



<!-- USAGE EXAMPLES -->

[comment]: <> (## Usage)

[comment]: <> (Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.)

[comment]: <> (_For more examples, please refer to the [Documentation]&#40;https://example.com&#41;_)



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Dan Tcheche - dancheche@hotmail.com

Project Link: [https://github.com/DanTcheche/your_social_life_bot](https://github.com/DanTcheche/your_social_life_bot)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/DanTcheche/your_social_life_bot/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/DanTcheche/your_social_life_botnetwork/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/DanTcheche/your_social_life_bot/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/DanTcheche/your_social_life_bot/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/DanTcheche/your_social_life_bot/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/dan-tchechenistky
[product-screenshot]: images/screenshot.png