# Stock_watch_Data_Viz
# Finance Explorer Dashboard

Finance Explorer is a web application built with Dash, a Python framework for building analytical web applications. It allows users to explore stock market data using candlestick charts and Bollinger Bands.

## Features

- Visualize stock market data with interactive candlestick charts.
- Analyze Bollinger Bands for selected stocks.
- Select multiple stocks simultaneously for comparison.
- Responsive design for optimal viewing experience on different devices.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.x
- Dash (```pip install dash```)
- Pandas (```pip install pandas```)
- Plotly (```pip install plotly```)
- Colorlover (```pip install colorlover```)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/finance-explorer-dashboard.git
    ```

2. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:

    ```bash
    python app.py
    ```

4. Open your web browser and go to http://localhost:8050 to view the dashboard.

## Usage

- Select one or more stocks from the dropdown menu to visualize their data.
- Explore the candlestick charts to analyze the opening, closing, highest, and lowest prices for each selected stock.
- Bollinger Bands are also displayed for each selected stock to analyze volatility and potential price trends.

## Screenshots

![Screenshot 1](screenshots/screenshot1.png)
![Screenshot 2](screenshots/screenshot2.png)

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project uses data from the [Plotly Dash Stock Ticker Demo](https://github.com/plotly/dash-sample-apps/tree/main/apps/dash-stock-tickers) repository.
- Special thanks to the [Dash](https://dash.plotly.com/) community for their excellent documentation and support.
