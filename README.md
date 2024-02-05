# iOS-map-clone
**Readme for LocationDetailsView.swift:**

1. **Description:**
   - This SwiftUI file, `LocationDetailsView.swift`, represents a detailed view of a selected map location. It includes information about the location, a look-around preview (if available), and options to open in Maps or get directions.

2. **Features:**
   - **Location Details:** Displays the name and title of the selected location along with a button to dismiss the view.
   - **Look-Around Preview:** Utilizes `MKLookAroundScene` to provide a preview of the selected location (if available).
   - **Action Buttons:** Allows users to open the location in Maps or initiate directions from the current location.

3. **Dependencies:**
   - **SwiftUI and MapKit:** The code relies on SwiftUI for the user interface and MapKit for map-related functionalities.
   - **Async/Await:** Utilizes Swift's async/await to handle asynchronous tasks, such as fetching look-around previews.

4. **Extensions:**
   - **LocationDetailsView Extension:** Defines an extension with a function (`fetchLookAroundPreview`) to asynchronously fetch look-around previews for the selected location.

5. **Preview:**
   - The code includes a SwiftUI preview for `LocationDetailsView`, allowing developers to visualize and test the detailed location view.

**Readme for ContentView.swift:**

1. **Description:**
   - This SwiftUI file, `ContentView.swift`, serves as the main view for a map-based application. It allows users to search for locations, view details, and get directions using MapKit.

2. **Features:**
   - **Map Interaction:** Utilizes SwiftUI's Map and MapKit to display the map, with markers for user location and search results.
   - **Search Functionality:** Users can search for locations using a TextField, triggering an asynchronous search using `MKLocalSearch` based on the entered text.
   - **Route Display:** Enables users to get directions from their current location to a selected map item. The route is displayed on the map with a blue polyline.

3. **Dependencies:**
   - **SwiftUI and MapKit:** The code relies on SwiftUI for the user interface and MapKit for map-related functionalities.
   - **Async/Await:** Utilizes Swift's async/await to handle asynchronous tasks, such as searching for places and fetching routes.

4. **Extensions:**
   - **ContentView Extensions:** Defines extensions for `CLLocationCoordinate2D` and `MKCoordinateRegion` to provide default values for user location and region.

5. **Preview:**
   - The code includes a SwiftUI preview for `ContentView`, allowing developers to visualize and test the main map view.

6. **Note:**
   - Ensure that the necessary permissions and configurations are set in the Xcode project, including location access and MapKit integration.

Feel free to customize and extend the code based on your application's requirements.
