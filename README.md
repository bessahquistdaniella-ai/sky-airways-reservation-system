# Sky Airways Reservation System

A responsive airline reservation website with a premium red-and-white visual theme. The layout is inspired by modern airline dashboards and uses original Sky Airways branding.

## Files
- `index.html` — the complete website, including HTML, CSS, and JavaScript.
- `README.md` — project and deployment instructions.

## Pages
- **Dashboard:** travel overview, flight/seat/booking counts, and popular destinations.
- **Find Flights:** search the sample schedule by route and date, then select a seat.
- **Reservations:** view confirmed bookings and cancel a booking.
- **Airline App:** airline overview and quick access to booking.

## Run locally
Keep `index.html` and `README.md` in the same folder and open `index.html` in a modern browser. No framework or build step is required.

## Deploy with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/(root)`, then save.

## Deploy with Vercel
1. Push the two files to a GitHub repository.
2. Import the repository in Vercel.
3. Select **Other** as the framework preset; no build command is needed.

## Project data
The website uses JavaScript arrays to keep the sample flights, seat availability, and reservations while the page is open. It is a front-end demonstration and does not connect to an airline, issue real tickets, or process payments. Data resets when the page is refreshed.


### Aircraft background
The supplied aircraft image is embedded directly in `index.html` as the homepage hero background, so the project still contains only two files and does not need a separate image asset.
