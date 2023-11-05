# Government Ports Reservation System

This script enables users to make reservations for parking spots at various government ports. It uses the Folium library to visualize the ports on a map and allows users to interactively reserve spots. The reservation data is stored in an HTML file for easy access and viewing.

## Dependencies

- Python 3
- Folium


1. Clone the repository or download the script file.

2. Run the script using a Python interpreter.

3. Follow the prompts to make reservations for parking spots at different ports.

4. The script will generate a map.html file visualizing the reserved spots and a reservation_data.html file containing the reservation information.

5. Open the reservation_data.html file in a web browser to view the reservation details.

## Notes

- The script uses a CSV file to store the locations of the government ports. Ensure that the port_locations.csv file is correctly formatted and accessible.
- Special permission is required to reserve more than 4 spots, and a passcode (admin123) is needed to authorize such reservations.
- The script prevents overbooking by checking the availability of parking spots before making a reservation.



