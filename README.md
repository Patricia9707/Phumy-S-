<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="src/styles.css" />
    <title>My weather application</title>
  </head>
  <style>
    h1 {
      font-size: 38px;
      font-weight: 900;
      margin: 0;
    }
    .weather-app {
      background: white;
      max-width: 600px;
      margin: 60px auto;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 30px 50px rgba(65, 50, 100, 0.08);
    }
    .search-input {
      background-color: #f9f7fe;
      border: none;
      color: rgba(39, 33, 66, 0.4);
      font-size: 16px;
      padding: 20px;
      width: 75%;
      border-radius: 6px;
    }
    .search-button {
      margin-left: 5px;
      font-size: 16px;
      background-color: #885df1;
      color: white;
      border: none;
      padding: 20px;
      line-height: 1;
      border-radius: 5px;
    }
    .detail {
      color: #f65282;
    }
    .current-temperature-icon {
      position: relative;
      top: -8px;
      font-size: 40px;
      margin-right: 10px;
    }
    .current-temperature-value {
      font-size: 80px;
      font-weight: bold;
    }
    .current-temperature-unit {
      font-size: 28px;
      position: relative;
      top: -38px;
    }
    .current-weather {
      display: flex;
      justify-content: space-between;
    }
    .current-details {
      color: rgba(39, 33, 66, 0.4);
      font-size: 16px;
      font-weight: 400;
      line-height: 24px;
    }
  </style>
  <body>
    <div class="weather-app">
      <header>
        <form>
          <input
            type="search"
            placeholder="Enter a city.."
            required
            class="search-input"
          />
          <input type="submit" value="Search" class="search-button" />
        </form>
      </header>
      <main>
        <div class="current-weather">
          <div>
            <h1>Paris</h1>
            <p class="current-details">
              Saturday 15:32, moderate rain <br />
              Humidity: <strong class="detail">87%</strong>, Wind:
              <strong class="detail">7.2km/h</strong>
            </p>
          </div>
          <div class="current-temperature">
            <span class="current-temperature-icon">☀️</span>
            <span class="current-temperature-value">24</span>
            <span class="current-temperature-unit">°C</span>
          </div>
        </div>
      </main>
      <footer>
        <p>
          This project was coded by
          <a href="#" target="_blank">Patricia Serakalala</a> and is
          <a href="#" target="_blank"> on GitHub</a> and
          <a href="#" target="_blank">hosted on Netlify</a>
        </p>
      </footer>
    </div>
  </body>
</html>
