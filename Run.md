Ensure you have the following installed:

Rust programming environment (Rustup)
Cargo (comes with Rust)
Git (for version control)
git clone https://github.com/yourusername/quantitative-analysis-model.git
cd quantitative-analysis-model
cargo build --release

Configuration
Before running the application, configure the necessary parameters:

API Keys:
Obtain API keys from Alpha Vantage, Yahoo Finance, etc.
Create a .env file in the project root directory and add your API keys
ALPHA_VANTAGE_KEY=your_alpha_vantage_key
YAHOO_FINANCE_KEY=your_yahoo_finance_key
Ensure your database is running (e.g., PostgreSQL).
Update the database configuration in config.toml or similar configuration file based on your setup.

Run command: cargo run
cargo run -- fetch-data
cargo run -- analyze
