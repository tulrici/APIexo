README
## Available Routes

The API has three available routes that return data in different formats:

- **JSON Route**: `/APIexercice/V1/json`
- **XML Route**: `/APIexercice/V1/xml`
- **CSV Route**: `/APIexercice/V1/csv`

You can access the routes by navigating to the respective URLs or by clicking buttons on the root route (`/`).

## How to Run

1. Install dependencies:
    ```
    npm install
    ```

2. Start the server:
    ```
    node index.js
    ```

3. Open your browser and navigate to:
    ```
    http://localhost:3000
    ```

4. From there, you can click the buttons to view the different formats (JSON, XML, CSV).

## Versioning

The API is versioned in the URL, with the current version being `V1`. You can access versioned routes like:
- `/APIexercice/V1/json`
- `/APIexercice/V1/xml`
- `/APIexercice/V1/csv`

## License

This project is for educational purposes and has no license attached.