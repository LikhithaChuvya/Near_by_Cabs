# Near_by_Cabs

### Project Description: Cab Locator Using Great Circle Distance Formula

#### Overview
The Cab Locator project is designed to efficiently determine the nearest available cabs to a user based on their current geographical location. This project leverages the Great Circle Distance formula to calculate the shortest path between two points on the surface of a sphere, providing accurate distance measurements for locations on Earth. The project is implemented in C++ and stores cab information in JSON files, ensuring both high performance and ease of data management.

#### Project Highlights

- **Great Circle Distance Formula**: Utilized to compute the shortest distance between two geographical coordinates (latitude and longitude). This formula is essential for accurately finding the nearest cabs by considering the curvature of the Earth.
  
- **Data Storage in JSON**: Cab information, including identifiers, coordinates, and availability status, is stored in JSON files. JSON is chosen for its simplicity and ease of use in data interchange, making the data easily accessible and modifiable.
  
- **Implementation in C++**: The project is coded in C++, a language known for its performance and efficiency. This ensures that the calculations and data handling are done quickly, providing real-time results to the user.

#### Detailed Features

1. **Cab Data Management**:
   - Each cab's information is stored in a JSON file, containing fields such as cab ID, current latitude, current longitude, and availability status.
   - The JSON format allows for straightforward parsing and updating of cab data.

2. **Distance Calculation**:
   - The Great Circle Distance formula is implemented to compute distances between the user's location and each cab's location.
   - This involves converting the latitude and longitude coordinates from degrees to radians and applying trigonometric functions to find the shortest path over the Earth's surface.

3. **Efficient Cab Retrieval**:
   - Upon receiving the user's current location, the system calculates the distance to each cab and identifies the nearest available ones.
   - The algorithm ensures that the results are accurate and the computations are optimized for quick performance.

4. **User Interface**:
   - A simple command-line interface is provided for users to input their current location.
   - The interface displays the nearest cabs along with their respective distances.

#### Benefits

- **Accuracy**: By using the Great Circle Distance formula, the project ensures that distance calculations are precise, taking the Earth's curvature into account.
- **Performance**: Implementation in C++ guarantees high-speed processing, which is crucial for real-time applications like cab locating services.
- **Scalability**: The use of JSON files for data storage allows for easy scalability, as new cab data can be added or updated with minimal effort.

#### Potential Extensions

- **Graphical User Interface (GUI)**: Enhancing the project with a GUI for better user experience.
- **Integration with GPS Devices**: Real-time updates of cab locations through GPS.
- **Database Integration**: Using a database system for managing larger datasets more efficiently.
- **Ride Booking Feature**: Extending functionality to allow users to book the nearest cab directly through the application.

This project serves as a robust foundation for building more complex ride-hailing systems and demonstrates the practical application of mathematical formulas and data management techniques in software development.
