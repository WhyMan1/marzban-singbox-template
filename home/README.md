<p align="center">
  <a href="https://github.com/oXIIIo/marzban-template/tree/master/home" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/oXIIIo/marzban-template/master/home/preview.gif">
      <img width="363" height="328" src="https://raw.githubusercontent.com/oXIIIo/marzban-template/master/home/preview.gif">
    </picture>
  </a>
</p>
<h1 align="center"/>Home Page Template for the <a href="https://github.com/Gozargah/Marzban">Marzban</a> Panel</h1>

<p align="center">
 <a href="./README.md">
 English
 </a>
 /
 <a href="./README-fa.md">
 فارسی
 </a>
</p>

## Table of Contents
- [Introduction](#introduction)
- [Installation Steps](#installation-steps)

# Introduction
A simple HTML template for the Marzban home page.

# Installation Steps
1. Download the template file.

```sh
sudo wget -N -P /var/lib/marzban/templates/home/ https://raw.githubusercontent.com/oXIIIo/marzban-template/master/home/index.html
```

2. Run the following commands in your server terminal:
```sh
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'HOME_PAGE_TEMPLATE="home/index.html"' | sudo tee -a /opt/marzban/.env
```
Alternatively, add the following values to the .env file located in the /opt/marzban directory:
```sh
CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"
HOME_PAGE_TEMPLATE="home/index.html"
```

3. Restart Marzban:
```sh
marzban restart
```

## Updating
To update the templates, simply repeat step 1.

# Contributors

<p align="center">
Thanks to the all contributors who have helped improve Sing-box template:
</p>
<p align="center">
<a href="https://github.com/WhyMan1/marzban-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=WhyMan1/marzban-template" />
</a>
</p>
<p align="center">
  Made with <a rel="noopener noreferrer" target="_blank" href="https://contrib.rocks">contrib.rocks</a>
</p>

# Support

<a href="https://nowpayments.io/donation?api_key=WE3KFT5-2VKMNSF-N1P4YQ6-24N82ZA&source=lk_donation&medium=referral" target="_blank">
  <img src="https://nowpayments.io/images/embeds/donation-button-black.svg" alt="Crypto donation button by NOWPayments">
</a>