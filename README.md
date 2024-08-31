<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/xSQUISHY/SquishyBOT-Instructions">
    <img src="https://squishybot.xyz/SQUISHY.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">SquishyBOT v1.0.1</h3>

  <p align="center">
    JS Discord All-In-One Bot
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
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>

  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- GETTING STARTED -->
## Getting Started

Before we begin, SquishyBOT has to be invited to the desired Discord server to function.
* SquishyBOT | Due to testing/development, more permissions are listed than usual.
  ```sh
  https://squishybot.xyz/invite
  ```

### Event Commands

1. AutoRole - Automatically set roles for new server members.
   ```sh
   /autorole <enable> <role> | Enable/Set role for autorole.
   /autorole <reset> | Disables autorole feature and removes data from database.
   ```
2. Auto-Delete - Configure automatic deletion of selected files.
   ```sh
   /autodelete <enable> <format> (.jpg, .png, .gif, .webm, .mp4) | Enable the bot to automatically delete specific file formats.
   /autodelete <disable> <format> (.jpg, .png, .gif, .webm, .mp4) | Disable auto-deletion for specific file formats.
   /autodelete permissions <include/exclude> <user/role> | Include/Exclude specific roles from being affected by auto-delete. (All Members By Default)
   /autodelete list <User & Roles/Formats> Display which User(s)/Role(s) are excluded from auto-delete or view enabled/disabled formats.
   ```

<p align="right">(<a href="#readme-top">Back to Top</a>)</p>



### Information Commands

1. GuildInfo - Automatically set roles for new server members.
   ```sh
   /guildinfo | Displayed detailed server-information.
   ```
2. UserInfo - Automatically set roles for new server members.
   ```sh
   /userinfo <@Mention or DiscordID> to display user's details.
   ```
3. Ping - Displays latency between Discord API and Bot's hosting server.
   ```sh
   /ping | Displays Discord & bot latency.
   ```
4. Emoji - Displays details such as Emoji name & ID.
   ```sh
   /emoji <:emoji:> | Displays emoji information.
   ```

### Utility Commands

   
### Fun Commands

1. Counting Game - Simple counting game for community interaction!
   ```sh
   /counting set-channel | Channel will be created and counting-game will be set to the channel.
   /counting allow-doubletext <enable/disable> | Toggle if the same user to count multiple times in a row.
   /counting current-number | Display current and next number of the active count.
   /counting <user> | Display a specific user's amount of chains broken.
   /counting leaderboard | Displays the server's highest streak of the server and who broke the most streaks.
   /counting cheaterboard | Displays which individuals maliciously attempt to destroy the counting chain.
   ```

### Gambling Commands
* Gambling is disabled by default, enable with /gambling enable. 
* Virtual currency is used for the gambling games.
1. Currency
   ```sh
   /currency balance <user:optional> | Display yours or another user's total balance.
   /currency redeem | A user can redeem $500 every 24 hours.
   /currency transfer <user> <amount> | Transfer currency to another user within the server.
   ```
1. Blackjack 
* Known Issues: Dealer's cards are displayed early. Split function doesn't work properly. Tied game payout doesn't return money.
   ```sh
   /blackjack <bet> | Start a game of blackjack w/ a set betting amount.
   ```
1. Slots 
   ```sh
   /slots <amount> | Start a game of slots w/ a set betting amount.
   ```
1. Roulette 
   ```sh
   /roulette <amount> | Start a game of roulette w/ a set betting amount, color option and optional number.
   ```
1. Coin-Flip (Player vs Player)
   ```sh
   /coinflip <user> <heads/tails> <amount> | Mention a user, select your coin side and your betting amount. User will be ping'd about their challenge and once accepted; game will start.
   ```
1. Rock Paper Scissors (Player vs Player)
   ```sh
   /rps <user> <r/p/s> <amount> | Mention a user, select your rps choice and your betting amount. User will be ping'd about their challenge and once accepted; opponent will choose their value of RPS and the game will start.
   ```

### Moderation Commands



### Administration Commands



### Owner Commands
1. Nuke | Duplicate & delete previous channel. 
   ```sh
   /nuke | Duplicate a channel w/ permissions & delete old channel. [Confirmation Message Included]
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

[SQUISHY's Discord](https://discord.gg/DjTgBxzhZr)

[SquishyBOT Discord Invite](https://squishybot.xyz/invite)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[squishybot-logo]: https://squishybot.xyz/SQUISHY.png
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
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
