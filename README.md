# Students-Enrollment-System-For-GPArvi
The online admissions &amp; student enrollment process in universities is quite tedious in terms of managing &amp; analyzing inquiries, planning strategies about marketing, and creating &amp; handling student records. Verifying student data &amp; creating merit list as per pre-defined criteria for various admission rounds as per the availability of the seats, maintaining effective communication with parents & students throughout the rounds, the entire process consumes a lot of time & errors are bound to arise while handling piles of paperwork & documents.

The Student enrollment system is designed to manage all the activities involved during the student enrollment process and combines them into a cloud-based system. The main objective of the enrollment system is to help staff members to enroll students and maintain their records.

To help university administrators simplify & automate the online admission process by managing & verifying student entries, documents, images, certificates, etc, and creating merit lists for various rounds as per the criterion student enrollment system.
#  [CyberDecodersSES]((https://github.com/Liladhar-s/Students-Enrollment-System-For-GPArvi/))
### A CyberDecodersSES project (Enrollment System) made by using [CodeIgniter](http://codeigniter.com).

[![Laravel Forge Site Deployment Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fforge.laravel.com%2Fsite-badges%2F2b682308-d55a-4064-a816-c8d5151c0366%3Fdate%3D1&style=plastic)](https://forge.laravel.com)

### Demo 

- [Mailto:Liladharsukhdeve17@gmail.com)

## Frameworks used
| Platform           | Framework                                                       |
|--------------------|-----------------------------------------------------------------|
| PHP Framework      | [CodeIgniter 3.1.5](http://codeigniter.com).                    |
| Admin UI Framework | [matrix-admin Bootstrap](http://matrixadmin.themedesigner.in/). |

## Library used


| Name                     | Repository                                                                                     |
|--------------------------|------------------------------------------------------------------------------------------------|
| Login Authentication     | [CodeIgniter-Ion-Auth](https://github.com/benedmunds/CodeIgniter-Ion-Auth).                    |
| Migration Authentication | [codeigniter-ion-auth-migration](https://github.com/iamfiscus/codeigniter-ion-auth-migration). |
| Error Log                | [CodeIgniter-Log-Library](https://github.com/appleboy/CodeIgniter-Log-Library).                |
| Excel Export             | [Codeigniter-Excel-Export](https://github.com/jiji262/Codeigniter-Excel-Export).               |
| Core My_Model            | [CodeIgniter-MY_Model](https://github.com/avenirer/CodeIgniter-MY_Model).                      |
| Translator               | [codeigniter3-translations](https://github.com/bcit-ci/codeigniter3-translations).             |

## Installation

- Create first a database named ``ci_capstone`` .
- then just run/execute the website, ``tables`` in ``database`` will automatically migrate.

- OR you can just import in database a sample data from ``sample_data/ci_capstone.sql``.

- then if you just/want to rename the folder name, you will be required to set/modify the base url as the same of name of your new folder name.

- Use PHP <= 7.0 to be working as expected, we accept PR for latest PHP support.

## Default Login

| Username      | Password           |
|---------------|--------------------|
| administrator | mypasswordisadmin1 |

## Screencapture
-Updated overview over the Admin Panel
![screenshot at 2017-04-09 21-26-03](https://cloud.githubusercontent.com/assets/8251344/24837640/50a98c44-1d6b-11e7-95b8-11c754f8c81d.png)

## Note:
### production ENVIRONMENT 
- compress html, for fast rendering page in live server 
- csrf_protection is enabled (set to TRUE), for prevent malicious/unnecessary behavior in submitting forms
- errors log save to database,then not directly seen in browsers,

### developing ENVIRONMENT
- compress html disabled, for easy monitoring html output (easy debugging)
- csrf_protection is disabled (set to FALSE), for easy submitting forms, for testing in big forms
- errors log disabled, directly prompt in browser,
- database set to localhost 

### ..
- all is this set up in application/config/{ENVIRONMENT_FOLDER_NAMES}/config.php


#### Any suggest/issue/problem don't hesitate to open an issue, even pull request. :)
