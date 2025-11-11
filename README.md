# ListenBrainz-OBS-Overlay
 A customizable OBS Overlay for ListenBrainz to show your currently playing song.

## Usage

0. Make a [ListenBrainz account](https://listenbrainz.org) if you don't have one already.
1. Download the [index.html](https://raw.githubusercontent.com/Nrwh1/ListenBrainz-OBS-Overlay/refs/heads/main/index.html) of the project.
2. Add a Browser Source to OBS and set it to wherever you downloaded the .html file. 
- Example: `file:///home/user/Downloads/ListenBrainz-OBS-Overlay/index.html`
3. Add configuration parameters to the URL of the Browser Source.
- Example: `file:///home/user/Downloads/ListenBrainz-OBS-Overlay/index.html?username=your_username&opacity=0.5&imageSize=200&infoAreaWidth=500&fontSize=35&refreshInterval=2&hideAlbumArt=false`
- Parameters:
    - `username`: Your ListenBrainz username. (Required)
    - `opacity`: Opacity of the overlay (0-1). Default is `1`.
    - `imageSize`: Size of the album art image. Default is `200`.
    - `infoAreaWidth`: Width of the info area. Default is `500`.
    - `fontSize`: Font size of the info area. Default is `35`.
    - `refreshInterval`: How often the song data is refreshed in seconds. Default is `2`.
    - `hideAlbumArt`: Whether to hide the album art. Default is `false`.