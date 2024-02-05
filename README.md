Code-Summary

1. **Fetching Country Information:**
   - The code listens for a click on the "search-btn" button, gets a country name from the input field, and fetches information about that country from the Restcountries API.
   - The fetched data is used to display details like flag, name, capital, continent, population, currency, and languages on the page.

2. **Event Listeners and Console Log:**
   - A console log prints "Btn clicked" when the "search-btn" button is clicked.
   - Two 'keypress' event listeners are set up:
     - One triggers a click event for "search-btn" when Enter is pressed.
     - The other attempts to hide an element with ID "info-main" when Enter is pressed, but this element is not in the provided HTML.

3. **Display Text Hiding:**
   - The code attempts to hide an element with ID "result" when the "search-btn" button is clicked by setting its visibility to 'hidden'.
   - This is useful if you want to clear or hide the displayed country information on a new search.
  


NOTE- Yet to optimise for mobile devices
