# Expressing Love - A Fun Interactive Web Project

This is a simple and fun web-based project designed to ask a special someone "Do you love me?" in a playful and interactive way.

## How it Works

The project consists of a series of HTML pages linked together. The user is first presented with a question and two options: "Yes" and "No".

- If the user clicks "Yes", they are taken to a page with a happy and loving message.
- If the user clicks "No", they are taken through a series of pages that playfully try to convince them to change their mind.
- On the final "No" page, the "No" button will move to a random position on the screen when the mouse hovers over it, making it very difficult to click.

## How to Use

1.  Clone or download the repository.
2.  Open the `index.html` file in your web browser.
3.  Follow the on-screen prompts.

## Project Structure

- `index.html`: The main page with the initial question.
- `yes.html`: The page displayed when the user clicks "Yes".
- `no1.html`, `no2.html`, `no3.html`: The pages displayed when the user clicks "No".
- `style.css`: The stylesheet for the pages.
- `script.js`: The JavaScript code that makes the "No" button move randomly.

## Step-by-Step Flow

1.  **`index.html`**: Asks "DO you love me? 🤗".
    -   **Yes**: Navigates to `yes.html`.
    -   **No**: Navigates to `no1.html`.
2.  **`no1.html`**: Asks the user to reconsider with "Please think again! 🙄".
    -   **Yes**: Navigates to `yes.html`.
    -   **No**: Navigates to `no2.html`.
3.  **`no2.html`**: Pleads with the user "Ek aur baar Soch lo! 😣" (Think one more time!).
    -   **Yes**: Navigates to `yes.html`.
    -   **No**: Navigates to `no3.html`.
4.  **`no3.html`**: Tries to persuade the user with "Baby Man jao na! Kitna bhav khaogi 😭" (Baby, please agree! How long will you play hard to get?).
    -   **Yes**: Navigates to `yes.html`.
    -   **No**: This button is special! When you hover over it, it moves to a random position on the screen, making it almost impossible to click.

## Purpose

This project is a fun and creative way to express your feelings to someone. It's a simple but effective way to bring a smile to their face.
