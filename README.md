# google-maps-autocomplete-api
New Simplified Example to Google Places Autocomplete and geocoding APi
### captainteknics@gmail.com
### +254715560734

# Google Places API Autocomplete with Address Components

This HTML file demonstrates the implementation of the Google Places API Autocomplete feature with address components. It allows users to input an address and retrieves detailed address information, including town, county, country, and latitude/longitude coordinates.

## Usage

1. Start by typing your address into the input field labeled "Enter Location".

2. As you type, the autocomplete feature will suggest matching addresses.

3. Select your address from the suggestions, and the form fields for town, county, country, and latitude/longitude will be automatically populated.

## Features

- **Autocomplete Address Input:** Utilizes the Google Places API to provide autocomplete suggestions as the user types their address.
  
- **Detailed Address Information:** Retrieves and displays town, county, country, and latitude/longitude components of the selected address.

- **Source Code:** Source code for this implementation is available on [GitHub](https://github.com/captainteknics).

## Dependencies

- Bootstrap CSS (from CDN)
- Google Maps JavaScript API (with Places library)

## Implementation

The HTML file includes form elements for user input and displays the retrieved address components. JavaScript code binds the autocomplete functionality to the input field and handles the retrieval and display of address information upon selection. 

```html
<script type="text/javascript" src="https://maps.googleapis.com/maps/api/js?libraries=places&key=YOUR_API_KEY"></script>
