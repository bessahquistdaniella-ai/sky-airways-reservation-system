# Sky Airways — African & Asian Destinations and Automatic Currency

This ZIP contains exactly two files: `index.html` and `README.md`.

## What's updated
- Added more African countries and cities, including Ghana, Nigeria, Kenya, South Africa, Egypt, Morocco, Tanzania, Uganda, Rwanda, Ethiopia, Senegal, Côte d’Ivoire, Cameroon, Algeria, Tunisia, Zambia, Botswana, Namibia and Mauritius.
- Added more Asian countries and cities, including Japan, China, India, Singapore, Malaysia, Indonesia, Thailand, the Philippines, South Korea, Pakistan, Bangladesh, Vietnam, the United Arab Emirates, Qatar, Saudi Arabia, Turkey, Israel, Sri Lanka and Nepal.
- Added departure-currency mapping for the supported regions. When a departure city is selected, the payment currency field updates automatically to that location's currency. The user can still manually change the currency afterward.
- Currency is based on the departure location, not the destination. This is a simulated fare display, not a live exchange-rate conversion.
- Existing cabin class, child-fare, group booking, seat selection and browser-local reservation features are retained.

## Update your hosted website
1. Extract the ZIP.
2. Replace `index.html` and `README.md` in your existing GitHub repository.
3. Commit the changes and wait for Vercel to redeploy.
4. Test by selecting departure cities such as Accra, Lagos, Nairobi, Johannesburg, Tokyo, Delhi, Dubai, London or Paris and checking the payment currency.

## Demo limitations
Flight routes and prices are simulated. No real payment is processed. Bookings are saved in the visitor's browser and are not shared between users or devices. Currency selection does not fetch live exchange rates.


## Cabin-class pricing update
- Economy uses the standard simulated base fare.
- First Class is priced at 3.5 times the Economy fare, so it is always substantially more expensive for the same simulated route.
- The cabin selection and fare summary label the First Class premium clearly.
- Prices are illustrative demo fares, not live airline prices.


## Automatic cabin fare preview fix
- Selecting Economy or First Class now immediately updates a visible fare preview on both the dashboard search form and the Find Flights form.
- The preview displays the adult fare, child fare, estimated total for the current passenger count, and the departure-based currency.
- First Class is always priced at 3.5 times the Economy base fare for the same simulated route/date.
- The preview refreshes when departure, destination, date, passenger count, cabin class or currency changes.
