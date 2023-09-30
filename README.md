<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Web Server: 
- PHP
- Database Server:
- Email Server:
- Operating System

![image](https://github.com/rod0929/osticket-prereqs/assets/146038941/b7aa9e49-25ca-4cc9-b7b2-343c61c3797c)

<h2>Configuration Steps</h2>



<p>

</p>
<p>
To install osTicket, your server must have Apache/LiteSpeed/IIS webserver (with the URL Rewrite module installed/enabled), PHP 8.1 - 8.2 (8.2 recommended), and MySQL 5.0 (or better) installed. If you are unsure whether your server meets these requirements, please check with your host or webmaster before proceeding with the installation.

You will need one MySQL database with valid user, password and hostname handy during installation. MySQL user must have FULL privileges on the database. If you are unsure whether you have these details or if the user has sufficient permissions, please consult your host or database admin before proceeding.
</p>
<br />

<p>
<img src=https://i.stack.imgur.com/Yp0rY.png
</p>
<p>
osTicket’s installation script will attempt to auto-detect paths and any permission issues. Please follow the instructions to finish up the installation process.

If the script spots any configuration errors then it will not allow you to continue until the errors are corrected.
If everything checks out, you will be presented with a form to fill in the required information.
If any errors occurs, go back and check the data entered.
On valid data the script will create and populate the database plus write a configuration file.
</p>
<br />

<p>
<img src=https://res.cloudinary.com/lwgatsby/f_auto/www/uploads/2021/07/osticket1-web-based-installation.png
</p>
<p>
To install osTicket, your server must have Apache/LiteSpeed/IIS webserver (with the URL Rewrite module installed/enabled), PHP 8.1 - 8.2 (8.2 recommended), and MySQL 5.0 (or better) installed. If you are unsure whether your server meets these requirements, please check with your host or webmaster before proceeding with the installation.

You will need one MySQL database with valid user, password and hostname handy during installation. MySQL user must have FULL privileges on the database. If you are unsure whether you have these details or if the user has sufficient permissions, please consult your host or database admin before proceeding.
</p>
<br />
