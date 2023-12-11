# Jeevika_500093984_CPT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify Clone</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }

        .container {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background-color: #212121;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .song {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }

        .song img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            object-fit: cover;
            margin-right: 10px;
        }

        .song-details {
            flex: 1;
        }

        .song-title {
            font-size: 1.2rem;
            margin-bottom: 5px;
        }

        .song-artist {
            font-size: 1rem;
            color: #888;
        }

        .controls {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .control-button {
            background-color: #1db954;
            color: #fff;
            border: none;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            cursor: pointer;
            display: flex;
            justify-content: center;
            align-items: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="song">
            <img src="album-cover.jpg" alt="Album Cover">
            <div class="song-details">
                <div class="song-title">Song Title</div>
                <div class="song-artist">Artist Name</div>
            </div>
        </div>
        <div class="controls">
            <button class="control-button">Play</button>
            <button class="control-button">Pause</button>
            <button class="control-button">Next</button>
        </div>
    </div>
</body>
</html>
The provided code is an HTML document with embedded CSS styling that creates a simple music player interface, mimicking a Spotify-like layout. Let's break down the key components and their styling:

HTML Structure:

The HTML structure starts with the <!DOCTYPE html> declaration, indicating that the document follows the HTML5 standard.
The <html lang="en"> tag sets the document's language to English.
The <head> section contains metadata such as character set, viewport settings for responsive design, and the document title.
The <body> section contains the actual content of the web page.
CSS Styling:

body: Sets the overall styling for the body, including font family, margin, padding, background color, and text color.
.container: Styles a container element with a maximum width of 600px, centered margins, padding, background color, border radius, and a box shadow for a card-like appearance.
.song: Configures the styling for a song section, displaying it as a flex container with space between items and centered alignment.
.song img: Styles the album cover image within the song section, setting dimensions, border-radius for a circular shape, and object-fit to cover.
.song-details: Styles the song details section within the song, allowing it to flex and take up remaining space.
.song-title and .song-artist: Define styles for the song title and artist name, setting font size and color.
.controls: Styles the control buttons section as a flex container with space between items and centered alignment.
.control-button: Styles the control buttons (Play, Pause, Next) with a background color, text color, border-radius for a circular shape, and cursor pointer.
Content:

The content within the .container div includes a song section with an image (album cover) and details (song title and artist name). Below that, there's a control section with three buttons for Play, Pause, and Next.
Overall, the code creates a visually appealing and responsive music player interface. It serves as a static representation, and to make it functional, additional JavaScript and server-side logic would be needed for handling user interactions, playing music, and managing the playlist.
