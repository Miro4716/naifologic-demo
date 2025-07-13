# NaifoLogic Demo

This project contains a static demonstration of the **NaifoLogic** v1.2 interface. It is designed as a lightweight HR panel showcasing login, dashboard, report and user management pages.

## Setup

No build step is required. Clone the repository and serve the files with any static HTTP server or simply open `login.html` in your browser.

```
# example using python
python3 -m http.server
```

Then visit [http://localhost:8000/login.html](http://localhost:8000/login.html).

## Dependencies

The demo uses only plain HTML, CSS and JavaScript so no external packages are needed. A modern web browser is sufficient.

## Viewing the Demo

1. Open `login.html` and enter the demo credentials defined in the script.
2. After logging in you will be redirected to `dashboard.html` where links lead to report and user pages.

## Extending for New HR Features

The panel can be expanded by adding additional HTML pages and updating the navigation links. Scripts can be placed inline or in separate JS files to simulate new features such as attendance tracking or performance metrics.

### Example steps

1. Create a new HTML page, e.g. `egitim.html` for training records.
2. Link to it from the navigation sections of existing pages.
3. Add JavaScript to fetch or display the new data.

