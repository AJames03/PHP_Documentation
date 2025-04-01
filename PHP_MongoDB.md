# PHP and MongoDB Integration

## What is PHP?
---
**According to:** https://www.w3schools.com/PHP/php_intro.asp
- PHP is an acronym for "PHP: Hypertext Preprocessor"
- PHP is a widely-used, open source scripting language
- PHP scripts are executed on the server
- PHP is free to download and use

## What is MongoDB?
---
**According to:** https://www.geeksforgeeks.org/what-is-mongodb-working-and-features/
- ***MongoDB*** is a powerful, flexible, and scalable *NoSQL database* that provides high performance and real-time data processing. Unlike traditional relational databases (RDBMS), MongoDB uses a document-oriented model, allowing developers to store and manage large volumes of unstructured or semi-structured data efficiently.

## How to Start?
---
### Step 1: Download the following:
**xampp:** https://www.apachefriends.org/download.html
**MongoDB Community Server:** https://www.mongodb.com/try/download/community
**MongoDB Shell:** https://www.mongodb.com/try/download/shell
**Composer:** https://getcomposer.org/download/
---
### Step 2: Install a PECL
- After you install the xampp you should go to **c:\xampp\php** and find the **php8ts.dll** to know the version of pecl that you need to install.
- But in some cases, even you install the pecl version but it is not working because the php which is in the xampp and your pecl version that you downloaded is not compatible to solve this problem here's the step by step:
    - ***Step 1:*** Go to Command Line or CMD 
    - ***Step 2:*** 
        ```sh
        cd c:\xampp\php
        ```
    - ***Step 3:*** 
        ```sh
        php -v
        ```
    - Output:
        ```sh
        PHP 8.2.12
        ```
- After you know the exact PHP version proceed to PECL Download Link or Website
**PECL download link:** https://pecl.php.net/package/mongodb
- Select the latest version, then click the DLL
- After that you will see the DLL version in the left side of the table then find the same version of it to your PHP Version.
- Then if you are confused which is you need to download either **Non Thread Safe (NTS)** or **Thread Safe (TS)**, back to the **php8ts.dll**. You'll see the TS after the php8. Therefore, you need to download the 8.2 version and make sure that it is Thread Safe (TS).
- Which you should choose x86 or x64 Architecture?
    - x86 is for 32 bit
    - x64 is for 64 bit

### Step 3: Integration of PHP and MongoDB:
---
- To integrate of it, you need to make sure that the Composer is already install.
- **NOTE:** Make sure that your Composer is install in directory ***c:\xampp\php\php.exe***

**Step 1:** Go to ***cd:\xampp\htdocs***, and create a folder.
**Step 2:** Inside the folder which you created, in the **Address bar** type **cmd**
**Step 3:** If you are in the command line type ***composer require mongodb/mongodb***
&nbsp;
---
**DISCLAIMER:** To make sure that there's no copyright issue I provide the links of website which our sources.
&nbsp;
##### Contributor: Aron James L. Betinol


