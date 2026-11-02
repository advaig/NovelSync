# NovelSync

## Project Goal

NovelSync is a Java application designed to help webnovel readers organize their reading progress and transfer book information to Goodreads. It addresses the difficulty of keeping reading records consistent across different reading platforms.

## MVP Features (Version 1.0)

- Extract novel information from saved NovelPhoenix HTML pages.
- Store novel titles and chapter progress locally.
- Display reading progress and completion percentages.
- Generate Goodreads-compatible CSV files for matched books.

## Future Plans (Version 2.0+)

- Automatically sync reading progress from NovelPhoenix accounts.
- Track reading progress changes over time.
- Support additional webnovel websites.
- Add reading statistics and visual graphs.

## Tech Stack

- **Java:** Main programming language.
- **jsoup:** Parse HTML and extract novel information.
- **Apache Commons CSV:** Generate formatted CSV exports.
- **Java File I/O:** Save and load reading information.
- **VS Code:** Development environment.
- **Git/GitHub:** Version control and documentation.

## Data Sources

NovelSync will initially use locally saved HTML pages from NovelPhoenix to access reading information. Goodreads will serve as the intended destination for exported book records, with users manually importing compatible CSV files.

## Planned Development

1. Set up the GitHub repository and Java environment.
2. Create a Novel class to represent reading data.
3. Implement HTML parsing using jsoup.
4. Add local CSV storage.
5. Create a command-line menu.
6. Implement reading progress calculations.
7. Generate Goodreads-compatible CSV exports.
8. Test the application and update documentation.

## Project Status

Currently in the planning and setup phase. Development will follow the milestones listed above.

## Project Documentation

- Eisenhower Matrix: `Eisenhower_Matrix.pdf`
- System Diagram: `System_Diagram.pdf`
