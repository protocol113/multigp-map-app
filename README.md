# multigp-map-app

Outline
Components
CourseDesigner.js: A reusable component that displays the satellite image and allows users to place and manipulate track components such as gates, flags, and obstacles.
ImagePreview.js: A component that displays a preview of a satellite image and allows users to zoom and pan to explore the image in more detail.
TrackList.js: A component that displays a list of saved tracks and allows users to select a track to view or edit.
TrackListItem.js: A component that displays a single item in the track list, showing the track name, image preview, and any additional metadata.
TrackGenerator.js: A component that generates new tracks based on a given field size and stores them as potential AI training examples.
Screens
HomeScreen.js: The main screen of the app, which displays a welcome message and links to the track list and course designer screens.
TrackDetailScreen.js: A screen that displays a single track, showing the satellite image and track components, as well as additional metadata and options to edit or delete the track.
TrackListScreen.js: A screen that displays the track list and allows users to create a new track, as well as edit or delete existing tracks.
TrackGeneratorScreen.js: A screen that allows users to input a field size and generate new tracks, which are saved as potential AI training examples.
Services
SatelliteImageService.js: A service that interfaces with Google's satellite imagery API, allowing the app to download and display high-resolution images of the selected location.
TrackService.js: A service that handles saving and retrieving tracks to and from local storage, as well as providing functions for importing and exporting tracks in various formats.
AIModelService.js: A service that manages the AI model used to generate new tracks, including training and testing the model, as well as providing functions for generating new tracks based on a given field size.
Functionality
Users can select a location on the map and display a satellite image of that location using Google's satellite imagery API.
Users can place and manipulate track components such as gates, flags, and obstacles on top of the satellite image.
Users can save and share tracks, as well as import tracks from a pool of existing tracks by using measurements provided by Multigp to determine the placement of track components.
Users can view and edit saved tracks, including metadata such as the track name and creator, as well as any additional notes or instructions.
The app is designed to be responsive and performant, with fast response times and efficient use of system resources.
The app is designed for FPV drone racing pilots, with a focus on assisting with planning and sharing tracks with other pilots. The UI and user experience are tailored to this specific audience.
The app is differentiated from existing apps by its niche focus on drone racing track planning, the ability to import tracks from a pool of existing tracks, and the ability to generate
