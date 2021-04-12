# SAD_SmallArtistsDiscovery

## Introduction
Our database application, named Small Artist Discovery, allows users to perform different types of searches for music and discover lesser known songs and artists. We collected songs, artists, albums, and genre information from the Free Music Archive, an online repository of royalty-free music.

## Description
The Small Artist Discovery application is web-based with an interface built from HTML, JavaScript, and CSS, while the backend is done using PHP. To run server and database in own desktop, Xampp is used, which allows programmers to work on a local server and test a local copies of websites using PHP code and MySQL databases. The application will feature a login system so users must create an account with username and password in order to access the application. This will allow us to store user data to create a more customized experience for each individual.
 
There will be 2 primary search features of the application: slider search and genre search. Slider search will ask the user to adjust 8 different sliders of different audio features to create a range that the returned song list will be filtered by. There is a possibility that nothing would return for song list, since none of the song matches within the range of all 8 features. Since the slider search result is precise and sensitive, instead of giving a result list in separate page, user can observe the changed list while they move the slider bar. As the user adjusts each slider bars, all the list of songs is returned that displays columns for song name, artist name, album name, and user preference. The user preference column contains a checkbox for each song - if the user likes a song, they can click the checkbox. A marked box is considered a “Like” for that specific song. The genre search begins by allowing the user to select one genre. Once the user presses “Search,” a results list is returned that looks identical to the slider search results, but this time only containing songs from the chosen genre. Songs for both searches will always be ordered in order of least popular to most popular, based on the number of listens of the songs.
	
The purpose of allowing users to “Like” songs is to help them keep track of what they have already listened to and prefer. This wouldn’t be complete without a functionality for the user to bring up a list of their current liked songs, so this is also implemented into the application. Furthermore, if user wants to remove certain song on User List, the user can mark checkbox that is labeled as “delete” and click the delete button.
  
## Interface
### SAD Initial Login, Registration, and Home page
![image](https://user-images.githubusercontent.com/48008528/114345254-59e02f80-9b9c-11eb-8db0-c43b76947b77.png)
### Slider Search Feature
![image](https://user-images.githubusercontent.com/48008528/114345293-6795b500-9b9c-11eb-8a39-b78c6a0a5681.png)
### Genre Search Feature
![image](https://user-images.githubusercontent.com/48008528/114345543-e68aed80-9b9c-11eb-9e45-893ba34ae899.png)
### User(group 16) Liked Song List
![image](https://user-images.githubusercontent.com/48008528/114345346-7b411b80-9b9c-11eb-9188-c02c545ff806.png)
