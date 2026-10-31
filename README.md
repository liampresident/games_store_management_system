# Games Store Management System

## Project Overview

A Python-based Games Store Management System developed as part of my university coursework.

The system provides an interactive interface for managing a game rental store, allowing staff to manage game inventory, customer subscriptions, rentals and bookings.

The application supports both video games and board games, with additional functionality for monitoring game popularity and rental activity.

## Features

- **Game Inventory:** View and manage video game and board game databases.
- **Game Search:** Search the inventory using game information.
- **Rental Management:** Process game rentals and returns while updating available stock.
- **Inventory Management:** Add new games, remove copies, and delete game records.
- **Customer Subscriptions:** Create and update Standard and Premium customer subscriptions.
- **Session Bookings:** Book sessions for customers.
- **Customer Feedback:** View customer feedback and ratings.
- **Popularity Tracking:** Monitor game ratings, total rentals and monthly rental activity.
- **Data Visualisation:** Generate graphs showing rental history and game usage.
- **Inventory Pruning:** Sort games by popularity, ratings and rental statistics to help identify usage trends.

## Technologies Used

- Python
- Google Colab
- Jupyter Widgets (`ipywidgets`)
- Matplotlib
- File handling and data processing

## How It Works

The application uses an interactive widget-based interface, allowing users to perform management operations without interacting directly with the code.

Game information is stored in separate text files for video games and board games. Additional files maintain rental records and popularity statistics.

The system reads these records into Python lists, processes the information and updates the relevant files when changes are made.

## Running the Project

1. Open the notebook in Google Colab.
2. Upload the required data files and supporting Python modules.
3. Run the notebook cells in order.
4. Run `inventoryPruning()` before opening the main menu on a fresh session.
5. Run `menu()` to launch the management interface.

**Important:** The project relies on its accompanying data files and supporting modules. The notebook alone may not contain everything needed to run the application.

## Development

This project involved developing an interactive management system with several connected areas of functionality.

Particular attention was given to:
- Organising interface components into reusable widget groups.
- Reading, searching and updating structured text-file data.
- Connecting interface buttons to their corresponding operations.
- Maintaining consistency between game inventory and rental records.
- Tracking historical rental activity and presenting it visually.
- Debugging issues involving widget state, output rendering and function scope.

## Future Improvements

- Migrate text-file storage to a relational database.
- Improve input validation and error handling.
- Introduce automated testing.
- Separate the application into more clearly defined Python modules.
- Improve the interface and make it usable outside Google Colab.

## Skills Demonstrated

Python programming, interactive GUI development, file handling, data structures, data visualisation, modular programming, event-driven programming and debugging.
