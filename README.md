# 🎬 Movies Recommender

This Python script suggests popular movie titles from IMDb based on a user's emotional preference (genre).

## 📌 Features

- Fetches movie titles from IMDb by genre
- Supports the following genres:
    - Drama
    - Action
    - Comedy
    - Horror 
    - Crime
   
- Displays few top movie titles for the selected emotion

## 🧠 How It Works

The script performs the following steps:

1. Prompts the user to enter a supported emotion/genre.
2. Maps the input to a predefined IMDb genre URL.
3. Sends a GET request to fetch the IMDb page.
4. Parses the page using BeautifulSoup to extract movie titles.
5. Displays the top results.


## 📸 Sample Image

![Screenshot_1](https://github.com/Aryanb10/Movies-recommender/blob/41f28fac051f02ae9af6f12c6a878002937b96ca/Movies-recommender/Screenshot%202025-06-27%20121118.png)


## 🧰 Possible Enhancements

- Add support for more genres or emotions.
- Allow filtering by release year or IMDb rating.
- Save output to a text or CSV file.
- Create a GUI using Tkinter or a web version with Flask.
- Handle pagination to fetch more results.

## 📄 License

This project is released under the MIT License. You are free to use, modify, and distribute this script with attribution.




