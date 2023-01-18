### Script to upload MODX Revolution for installation in 1 Click

#### This script is intended for initial installation. Install the Updater extra for upgrades.


Place the install.php file in the same directory as your site root. Load it in your browser and select the version you want to install. (i.e. mydomain.com/install.php)

The script will download the selected version from the MODX respository, unzip it in the same location, then forward you to the MODX setup. The install.php script will automatically delete itself.

#### This script is intended for initial installation. Install the Updater extra for upgrades.

In order to be able to directly download the MODX zip archive from the MODX repository, your server must have either allow_url_fopen or cURL enabled.

In order to be able to unzip the downloaded MODX archive, your PHP must be at least version 5.2, it must have been compiled to include the zip extensions, and have the zip extension enabled.

You may need to change the permissions for newly created folders on line 184. For example, your server may require directory permissions of 0755.

Changelog:

Version 1.6.33
(2022/01/18)
- Add link for Revo 3.03 pl

Version 1.6.32
(2022/11/17)
- Add link for Revo 3.02 pl

Version 1.6.31
(2022/04/28)
- Add link for Revo 3.0.1 pl
- Add link for Revo 2.8.4 pl

Version 1.6.30
(2022/03/30)
- Add link for Revo 3.0.0 pl

Version 1.6.29
(2022/02/03)
- Add link for Revo 3.0.0 rc2

Version 1.6.28
(2022/01/20)
- Add link for Revo 3.0.0 rc1

Version 1.6.27
(2021/05/28)
- Add links for Revo 2.8.3

Version 1.6.26
(2021/04/28)
- Add links for Revo 2.8.2
- Remove links for 2.7.x

Version 1.6.25
(2020/10/22)
- Add links for Revo 2.8.1

Version 1.6.24
(2020/10/06)
- Add links for Revo 2.8.0
