# Simple Appointment Calendar

A simple, open-source appointment calendar that runs entirely in the browser.

No sign-up, no server, no database. Open `index.html` and start adding appointments. Your appointments are saved in your browser's local storage only.

## Features

- Add an appointment with a title, date, time, and optional note
- See appointments sorted by date and time
- Filter appointments by a single date, or show all upcoming appointments
- Delete an appointment
- Export all appointments as an `.ics` file for use in other calendar apps
- Works offline after the page is loaded — no account or backend needed

## How to use

1. Open `index.html` in any modern browser, or serve the folder with any static file server, for example:
   ```bash
   python3 -m http.server 8000
   ```
   Then open http://localhost:8000
2. Fill in the title, date, and time, and click **Add appointment**.
3. Use the date filter to see one day, or click **Show all** to see everything.
4. Click **Export .ics** to download your appointments.

## Tech

- Plain HTML, CSS, and JavaScript — no framework, no build step, no dependencies.

## Status

This is a new, small project created on 24 November 2026. It has no users, stars, or contributors yet. It is published as open source under the MIT License so anyone can use it, suggest changes, or contribute.

## Contributing

Issues and pull requests are welcome. Please keep changes small and focused, and test the page in a browser before submitting.

## License

MIT — see `LICENSE`.
