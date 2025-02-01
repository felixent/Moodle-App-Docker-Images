# About
Moodle is open source under the GPL licence. Everything we produce is available for you to download and use for free. Moodle Project is supported by over 90 certified Moodle Partners globally.

- Docs: https://docs.moodle.org/405/en/Main_page
- Plugins: https://moodle.org/plugins/
- Apps: https://download.moodle.org/mobile/
- Dev: https://moodledev.io/
- API: https://moodledev.io/docs/5.0/apis
- SourceCode: https://download.moodle.org/releases/latest/
- Git Admin: https://docs.moodle.org/405/en/Git_for_Administrators

## Basic Requirements

 1. Need a working web server (e.g. Apache, Nginx, OpenLiteSpeed), a database (e.g. MySQL, MariaDB or PostgreSQL) and have PHP configured. See the release notes in the dev docs for software requirements.
 2. Requires a number of PHP extensions. 
 3. For Moodle 4.5.1+, PHP 8.1, MariaDB 10.6.7 or MySQL 8.0 or Postgres 13 or MSSQL 2017 or Oracle 19c
Moodle checks early in the installation process and you can fix the problem and re-start the install script if any are missing.
 4. Want Moodle to send email (you probably do) you need a working Sendmail (Unix/Linux) on your server or access to an SMTP mail server.

## Getting Moodle
Two basic options: Download your required version from https://download.moodle.org/ ... OR
Pull the code from the Git repository (recommended for developers and also makes upgrading very simple):
```
git clone -b MOODLE_403_STABLE git://git.moodle.org/moodle.git 
```
...this fetches a complete copy of the Moodle repository and then switches to the 4.5 Stable branch. 
### Direct Download
```
https://packaging.moodle.org/stable404/moodle-latest-404.zip
```
```
https://packaging.moodle.org/stable405/moodle-latest-405.zip
```
