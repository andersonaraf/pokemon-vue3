# Pokedex Learning Project

This is a Pokedex learning project built using Laravel 11 for the backend and Vue.js with Inertia.js for the frontend. This project aims to help developers learn how to integrate Laravel with a modern frontend framework using Inertia.js, creating a seamless single-page application (SPA) experience.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Project](#running-the-project)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Pokedex Learning Project is designed to help developers understand the basics of Laravel and Vue.js integration using Inertia.js. The application serves as a Pokedex, a digital encyclopedia of Pokémon, allowing users to view and search for different Pokémon.

## Features

- View a list of Pokémon
- Search for Pokémon by name
- View detailed information about each Pokémon
- Responsive design using Vue.js

## Requirements

- PHP 8.2 or higher
- Composer
- Node.js and npm
- Laravel 11
- Inertia.js
- Vue.js 3

## Installation

Follow these steps to set up the project locally.
```bash
composer install
```
```bash
npm install
```
### Set up environment variables
Copy the .env.example to .env and update the necessary configuration, such as database credentials
```bash
cp .env.example .env
```
```bash
php artisan key:generate
```
### Clone the repository

```bash
git clone https://github.com/andersonaraf/pokemon-vue3.git
cd pokemon-vue3
```

### Running the Project
In the project root directory, run the following commands to start the Laravel server and the frontend server.
```bash
php artisan serve
```
In the browser open http://localhost:8000
