# RestStop

![RestStop Logo](logo.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

RestStop is a web application that allows users to find nearby bathrooms in their area quickly and efficiently. The idea is inspired by the "mapty" app created by Jonas Schmedttman, which has been repurposed to serve this specific need.

Whether you're on a road trip, exploring a new city, or simply in need of a restroom in an unfamiliar area, RestStop is here to help you find the nearest facilities with ease.

## Features

- **Interactive Map:** Utilize an intuitive map interface to view nearby bathrooms.
- **Filtering Options:** Narrow down your search by facilities type, accessibility, and user ratings.
- **User Reviews and Ratings:** Contribute to the community by leaving reviews and ratings for bathrooms you've visited.
- **Save Favorite Restrooms:** Keep track of your preferred restrooms for future reference.
- **Mobile-Friendly:** Access RestStop on the go with a responsive design optimized for mobile devices.

## Getting Started

### Prerequisites

Before getting started with RestStop, make sure you have the following installed:

- Node.js and npm
- MongoDB
- Git (optional)

### Installation

1. Clone the repository (if you haven't already):

```bash
git clone https://github.com/yourusername/reststop.git
```

2. Navigate to the project directory:

```bash
cd reststop
```

3. Install the necessary dependencies:

```bash
npm install
```

4. Set up the database:

   - Make sure MongoDB is running on your system.
   - Configure the database connection in `config/config.env` if needed.

5. Start the application:

```bash
npm start
```

The application should now be running locally.

## Usage

1. Open your web browser and go to `http://localhost:3000`.
2. Sign up or log in to your RestStop account.
3. Use the map to locate nearby bathrooms in your area.
4. Filter results based on your preferences (e.g., accessibility, user ratings).
5. Click on a bathroom marker to view details and leave a review.

## Contributing

We welcome contributions from the community. If you have any ideas, bug reports, or feature requests, please [open an issue](https://github.com/yourusername/reststop/issues) or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the license terms.

---

Happy RestStopping! 🚽✨
