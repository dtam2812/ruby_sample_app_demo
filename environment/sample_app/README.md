# Sample App

Sample application built while following [*Ruby on Rails Tutorial: Learn Web Development with Rails*](https://www.railstutorial.org/) by [Michael Hartl](https://www.michaelhartl.com/).

> [!NOTE]
> The book (6th edition) targets Rails 6.0 and Ruby 2.7 / 3.0.  
> This project is updated to **Ruby 4** and **Rails 8**, so some steps differ from the book (e.g., Bundler configuration, SQLite database setup, and asset handling via Propshaft/Importmap).

---

## Versions & Requirements

- **Ruby**: `4.0.9` 
- **Rails**: `8.1.4.1`
- **Bundler**: `4.0.23`

---

## Getting Started

1. **Clone the repository and install dependencies:**
   ```bash
   bundle install
   ```

2. **Setup and migrate the database:**
   ```bash
   rails db:migrate
   ```

3. **Run the test suite:**
   ```bash
   rails test
   ```

4. **Start the local server:**
   ```bash
   rails server
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

