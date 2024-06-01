<h3 align="center">UltraBomber</h3>

  <p align="center">
    UltraBomber - #1 Bangladeshi SMS bomber.
    <br />
    <a href="https://github.com/detasploit/ultrabomber/blob/main/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://detasploit.github.io/ultrabomber/">View Demo</a>
    ·
    <a href="https://detasploit.github.io/ultrabomber/issues">Report Bug</a>
    ·
    <a href="https://detasploit.github.io/ultrabomber/issues">Request Feature</a>
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

UltraBomber - #1 Bangladeshi SMS bomber.

### Built With

* [Bootstrap](https://getbootstrap.com)
* [Bootstrap Icons](https://icons.getbootstrap.com)
* [JQuery](https://jquery.com)

## Major Update 
- Numbers are now automatically trimmed to 10 digit in the `script.js` file. Upon submission, the 0 in the beginning is removed. So while setting up the APIs, please add 0 manually to make it workable.
### Using Github Pages

To host your bomber directly into Github Pages 
- Click on `Use this template` on the top corner of this repository.
- Select your desired repository name.
- Go to the `Pages` section of your repository from settings.
- Select branch `main` and choose a theme to publish your website.

### Local development

1. Clone the repository
   ```sh
   git clone https://github.com/detasploit/ultrabomber.git
   ```

<!-- USAGE EXAMPLES -->
## Usage
### Method 1 [Using APIS array variable]
1. Edit APIs in the `script.js` to make the bomber work.
   ```js
   const APIS = [
        {
            method: "POST",
            url: `https://your-api-endpoint/?phone=+88${mobile}`,
            body: `type=register&phone=${mobile}`
        }
   ]
   ```
### Method 2 [Using APIS json files from any URL]
Follow the example APIS.json file in the assets directory and keep the same format in your custom api.json file to work. 

_For more examples, please refer to the [Script.js Example](https://github.com/detasploit/ultrabomber/blob/main/assets/script.js)_

<!-- LICENSE -->
## License

Distributed under the GNU GENERAL PUBLIC LICENSE License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

**SowmikSudo** ***(Maintainer)***
- [![Telegram](https://img.shields.io/badge/Telegram-ID-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/ign0r3dh4x0r)&nbsp;
- [![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SowmikSudo)&nbsp;

**detasploit**
- [![Facebook Page](https://img.shields.io/badge/Facebook-Page-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/detasploitx)&nbsp;
- [![Telegram](https://img.shields.io/badge/Telegram-Channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/detasploitx)&nbsp;
