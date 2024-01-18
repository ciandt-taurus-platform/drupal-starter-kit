# Drupal Project Starter Kit

## Overview
This project serves as a simplifier for creating new Drupal projects using Composer. It's designed to streamline the process of setting up a Drupal site by executing a single command. This tool automates the setup, making it quicker and more efficient to kickstart your Drupal project.

## Getting Started

### Prerequisites
```
Git version ^2.34
Composer version ^2.5
```

### Installation

#### Clone the Repository

Begin by cloning this repository to a local directory of your choice:

```
git clone https://github.com/ciandt-taurus-platform/drupal-starter-kit.git [local-directory]
```

#### Create the Project
Navigate to where you want to create the project:

```
composer create-project --repository-url=[local-directory]/packages.json drupal/starter-kit [project-name]
```

👉 Replace [local-directory] with the path to your cloned repository.
drupal/starter-kit is the vendor parameter and should remain unchanged.

👉 Replace [project-name] with your desired project name.

## Included Modules

This simplifier includes the following modules by default, along with Drupal core 10.0.x:


- Admin Toolbar
- Pathauto
- Seckit
- COOKiES Consent Management
- Config Split
- Metatag
- Google Tag
- Redirect
- Simple XML sitemap
- Social Media Links Block and Field
- FAQ Field
- Shield
- CAPTCHA
- reCAPTCHA
- Devel (used as dev dependency)
- Advanced CSS/JS Aggregation

## Additional Recommended Modules

You may choose to install additional modules recommended for drupal/starter-kit. To view these recommendations, use the command:

```
composer suggest --by-package
```

Recommended modules include:

- Real-time SEO for Drupal (YOAST SEO)
- SEO Checklist
- Field Group
- Webform
- Layout Paragraphs
- Display Suite
- Drush (Drush, the Drupal shell tool, is also included in this setup for effective management of your Drupal site from the command line.)