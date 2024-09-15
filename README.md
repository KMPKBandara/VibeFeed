# VibeFeed News Application

VibeFeed is a simple and responsive web application built using React JS and Bootstrap, integrated with the News API to fetch and display the latest news. The app provides news updates in various categories such as Technology, Business, Health, Sports, and Entertainment.

## Features

- News Categories: Browse through various news categories (Technology, Business, Health, Sports, Entertainment).
- Category Navigation: Clicking on a category will display news related to that particular section.
- Read More: Clicking the "Read More" button for any news article will redirect users to the full article.
- Responsive Design: The application is fully responsive, making it accessible on mobile, tablet, and desktop devices.

## Tech Stack

- React JS: For building the UI components.
- Bootstrap: For responsive design and styling.
- News API: To fetch the latest news updates.
  
## Getting Started

### Prerequisites

- Node.js installed on your machine.
- A News API key from [News API](https://newsapi.org/).

### Installation

1. Clone the repository:

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add your **News API key**:
    ```bash
    VITE_API_KEY=your_news_api_key
    ```

4. Start the application:
    ```bash
    npm run dev
    ```


## Usage

- Browse Categories: Choose from different news categories by clicking on the category name in the navigation bar.
- Read More: To read the full news article, click on the "Read More" button, which will take you to the original news article source.
  
## API

This project uses the [News API](https://newsapi.org/) to fetch news articles. Ensure you have an active API key.
