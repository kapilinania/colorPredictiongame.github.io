# 🎨 Color Prediction Game
![image](https://github.com/kapilinania/colorPredictiongame.github.io/assets/67285213/3499201e-31ea-4f8b-8deb-60f229514501)


Welcome to the Color Prediction Game! This interactive game allows users to predict the next color in a sequence of three colors: 🟢 green, 🟣 violet, and 🔴 red.

## Features

- Users can register and login to the game.
- Users can make predictions about the next color in the sequence.
- The game generates a sequence of three colors: 🟢 green, 🟣 violet, and 🔴 red.
- Users earn points based on the accuracy of their predictions.
- Admin panel for managing games, users, and predictions.

## Technologies Used

- Laravel Framework
- MySQL Database
- HTML, CSS, JavaScript (Frontend)
- Laravel Backpack (Admin Panel)

## Installation

1. Clone the repository:
git clone <repository-url>

css
Copy code

2. Navigate to the project directory:
cd color-prediction-game

markdown
Copy code

3. Install dependencies:
composer install
npm install

markdown
Copy code

4. Create a copy of the `.env.example` file and rename it to `.env`. Update the database credentials in the `.env` file.

5. Generate application key:
php artisan key: generate

markdown
Copy code

6. Run database migrations and seeders:
php artisan migrate --seed

7. Start the development server:

php artisan serve


8. Access the game in your browser at `http://localhost:8000`.

## Usage

1. Register a new account or login if you already have an account.
2. Make predictions about the next color in the sequence (🟢, 🟣, 🔴).
3. Earn points based on the accuracy of your predictions.
4. View your score and ranking on the leaderboard.
5. Admins can manage games, users, and predictions from the admin panel.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.




