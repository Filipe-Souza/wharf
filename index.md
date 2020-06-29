# Wharf - Alpha - Web UI for Dokku

1. [About this fork](#about-this-fork)
2. [Pre requisites](#pre-requisites)
3. [Setup](#setup)
4. [Helpful hints](#helpful-hints)
5. [Enabling Github auto-deploy webhooks](#enabling-github-auto-deploy-webhooks)
6. [Development setup](#development-setup)
7. [Roadmap](#roadmap)
8. [Screenshots](#screenshots)

This is a forked version of Wharf. Check out the original project to more details.

Wharf is an web frontend for [Dokku](http://dokku.viewdocs.io/dokku/). 

Dokku it is a great Heroku-like tool, with a extensive command line operation. This web interface aims to 
simplify some routine tasks when managing applications on Dokku.


## About this fork

The original Wharf project has the functional backend needed. But the front-end was not usable at the time. So, this project
idea is to bring a modern and simple as possible front end interface to Wharfs functions.

## Features

With Wharf, you can manage all application generic activities with a web interface: application listing,
linking, state management, deploys and more to come.

## Screenshots

### Initial setup
![](screenshots/ssh_key_setup.png)

### Application list
![](screenshots/app_list.png)

### Information navbar
![](screenshots/navbar.png)

![](screenshots/navbar_notification.png)

### Global environment variables
![](screenshots/global_env_var_list.png)

### Generic task log
![](screenshots/generic_task_log_view.png)

### Application details

Overview
![](screenshots/app_details_overview.png)

Logs
![](screenshots/app_log_output.png)

LetsEncrypt and SSL
![](screenshots/app_domains_ssl.png)

Environment variables
![](screenshots/app_env_vars.png)

Environment variables
![](screenshots/app_env_vars_form.png)

Application database link example
![](screenshots/app_specific_linking.png)

