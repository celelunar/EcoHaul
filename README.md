# EcoHaul
🗑️🍃 A Trash Collection Application Made with Laravel 11, Bootstrap 5, and MySQL.

EcoHaul is a trash collection management application designed to encourage sustainable waste disposal practices by providing faster and more efficient access to recycling service providers and raise public awareness about the importance of environmental protection through recycling practices. The app allows users to schedule waste pickups, locate drop-off points, redeem recycling points for rewards, and keep track of their recycling history.

## Notice
This application was created as a part of two university classes' final project, namely Software Engineering and Web Programming. The primary goal is to apply theoritical knowledge of software development, user interface design, and environmental sustainability into a real-world solution. This project allows the contributors to gain practical experience in building a comprehensive platform that addresses social and environmental issues while meeting academic requirements.

## Contributors
- 2501971742 - Alisha Zahra Saadiya
- 2502008630 - Cyntia Angelica
- 2501975620 - Diva Nabila Henryka
- 2540121322 - Lovina Anabelle Citra
- 2502037864 - Syarani Afa Natira Kusumah

## Features

### 1. Sign In and Sign Up
- **New Users**: Can easily register by filling out a form that collects basic information such as name, age, gender, home address, email, phone number, and password. Users can also sign up using their social media accounts.
- **Existing Users**: Can log in using their email and password or through linked social media accounts.

### 2. Redeem Points
- Users earn points every time they utilize pickup or drop-off services for their recyclable waste.
- Points are awarded based on the amount of waste provided.
- Users can redeem accumulated points for rewards or shopping vouchers.

### 3. Location
- The app provides an interactive map that shows nearby drop-off points and available pickup services in the user's area.
- Detailed information about each location, including operational hours, types of accepted waste, and contact details, is available.

### 4. Pick Up
- Users can schedule a waste pickup at their location by a recycling service provider.
- They can select a convenient time for pickup, making waste management easier.
- Real-time notifications keep users informed about the pickup status and confirmation from the service provider.

### 5. Drop Off
- Users can view and get directions to nearby drop-off locations, such as recycling centers, waste banks, and collection points.
- The app provides a map with interactive directions to make reaching drop-off points easier.

### 6. History
- A complete history of all pickups and drop-offs, including dates, waste amounts, and points earned, is accessible.
- Users can also view rewards or vouchers claimed through point redemption.

### 7. Profile
- Users can update their personal information such as name, home address, phone number, and email.
- Options are available to configure notification preferences, language settings, and privacy settings.
- Users can change their password and activate additional security features like two-factor authentication.

### 8. Newsletter
- Periodic newsletters are sent to users to provide educational materials on recycling, effective waste management tips, and the latest environmental news.
- This feature aims to enhance user awareness and knowledge about sustainable waste management and recycling efforts.

## Versions Used
- **PHP**: 8.2.12
- **npm**: 10.5.0
- **Composer**: 2.7.4
- **Laravel**: 11

## Installation

### Prerequisites
Ensure you have the following installed on your local machine:
- PHP 8.2.12 or higher
- npm 10.5.0 or higher
- Composer 2.7.4 or higher
- Laravel 11

### Steps to Set Up Locally
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/EcoHaul.git
    ```

2. Navigate to the project directory:
    ```bash
    cd EcoHaul
    ```

3. Install dependencies using Composer:
    ```bash
    composer install
    ```

4. Install front-end dependencies using npm:
    ```bash
    npm install
    ```

5. Set up the environment variables:
    ```bash
    cp .env.example .env
    ```

6. Generate the application key:
    ```bash
    php artisan key:generate
    ```

7. Run migrations to set up the database:
    ```bash
    php artisan migrate
    ```

8. Serve the application locally:
    ```bash
    php artisan serve
    ```
