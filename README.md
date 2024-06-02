# PawsitiveCare 🐾

Welcome to **PawsitiveCare**, your premier pet walking service application! Our mission is to bring joy and care to every pet while providing a seamless experience for pet owners and dog walkers. This repository contains the full-stack web application that powers PawsitiveCare, designed with Node.js, Express, MongoDB, and EJS templating.

## Backgrounder on how to front end a Mongo Database with an Express Web Server
[Connecting Nodejs to MongoDB with Express](https://www.perplexity.ai/page/Connecting-Nodejs-to-vEHEEa7yTAOgCqRIXseLrw)

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Pet Management**: Easily add, update, and delete pets from the system.
- **Dog Walker Management**: Manage the list of available dog walkers.
- **Client Management**: Keep track of pet owners' information.
- **Appointment Scheduling**: Book, view, update, and cancel appointments with ease.
- **Responsive Design**: Enjoy a seamless experience across all devices.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v12 or higher)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ProfessorBrownBear/PawsitiveCare.git
   cd PawsitiveCare/pet-walking-service-app


### Install NPM packages:

npm install
Set up your MongoDB connection:

Create a .env file in the root directory.

Add your MongoDB URI to the .env file:

env
Copy code
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/PawsitiveCare?retryWrites=true&w=majority
Usage
Start the server:


npm start
Open your browser and navigate to http://localhost:3000.

##### Routes
- Home Page: http://localhost:3000
- Pet Management: http://localhost:3000/pets
- Dog Walker Management: http://localhost:3000/dogwalkers
- Client Management: http://localhost:3000/clients
- Appointments: http://localhost:3000/appointments
- Add Appointment: http://localhost:3000/appointments/add
- Update Appointment: http://localhost:3000/appointments/update/:id

  
**Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

  
### License
Distributed under the MIT License. See LICENSE for more information.

# Acknowledgments
Hat tip to anyone whose code was used
Inspiration: Our lovable pets who inspired this project
The amazing community that supports open source projects

## PawsitiveCare: Where every pet is treated with pawsitive care! Let's make the world a better place for our furry friends, one walk at a time. 🐶❤️
