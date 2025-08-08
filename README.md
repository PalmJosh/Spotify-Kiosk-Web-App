<a href="https://spotify-react-web-client.onrender.com/" target="_blank">
  <p align="center">
 
  </p>
</a>

<p align="center">

</p>

# 🎧 Spotify Kiosk Web App

> [!IMPORTANT]
> Spotify Playback requires users to authenticate with a valid Spotify Premium subscription.


## 🚀 Features

⚡ **Music Playback**: Play songs in real-time using the Spotify Playback SDK.

⚡ **Playback Controls**: Play, pause, next, previous, shuffle, and repeat functionalities.

⚡ **Music Browsing**: Search and explore songs, artists, albums, and playlists.

⚡ **Playlists Management**: Create, edit, and delete personalized playlists.

⚡ **Saved Playlists and Albums Access**: View and play your saved playlists and albums.

⚡ **Liked Songs**: Mark tracks as "liked" and access a dedicated playlist for liked songs.

⚡ **Playback Devices**: Switch between different playback devices (desktop, mobile, smart speakers).

⚡ **Follow/Unfollow Artists**: Follow and unfollow artists to get updates on their new releases.

⚡ **Artist and Album Pages**: Dedicated pages for artists and albums, showcasing top songs, discography, and related artists.

## 🛠 Technologies Used

🎵 React: For building the user interface with reusable components.

🎵 React Redux: For global state management and smooth data flow across the app.

🎵 <a href="https://developer.spotify.com/documentation/web-api/">Spotify Web API</a>: To fetch data like playlists, albums, and user information.

🎵 <a href="https://developer.spotify.com/documentation/web-playback-sdk/">Spotify Playback SDK</a>: For real-time music playback control within the web client.



## ⚙️ Installation & Setup

To run this project locally, follow these steps:

1. Clone this repository:

   ```bash
   clone 
   ```

2. Navigate to the project directory:

   ```bash
   cd spotify-kiosk-web-app
   ```

3. Install dependencies:

   ```bash
   yarn install
   ```

4. Set up your Spotify Developer account and create a [new app](https://developer.spotify.com/dashboard/applications) to obtain your **Client ID** and **Redirect URI**. Add these to an `.env` file in the root of your project:

   ```
   REACT_APP_SPOTIFY_CLIENT_ID=<your id>
   REACT_APP_SPOTIFY_REDIRECT_URL=<your redirect uri>
   ```

5. Start the development server:

   ```bash
   yarn start
   ```

6. Open your browser and navigate to `http://localhost:3000`.

## 🤝 Contributions

Based on [Spotify React Web Client](https://github.com/francoborrelli/spotify-react-web-client?tab=readme-ov-file) from francoborelli

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
