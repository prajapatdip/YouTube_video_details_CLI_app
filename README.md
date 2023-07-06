
# CLI Application using Golang.

I have developed a CLI (Command-Line Interface) application in Go for managing YouTube video details. The application allows users to store information such as video ID, title, URL, image URL, and description. To persist the data, I have utilized a JSON file named **"video.json"**. This application provides functionality to display details of all videos or specific videos based on their IDs. Additionally, users can manually add video details through the CLI interface. The implementation utilizes several Go packages including **"fmt"**, **"io/ioutil"**, **"encoding/json"**, and **"flag"**.

## Run Locally

Fetch the source code.

```
    git clone https://github.com/prajapatdip/YouTube_video_details_CLI_app.git
    cd YouTube_video_details_CLI_app
```

Running the application.

```
    cd videos
    go build
    alias video='./videos'
```
## Demo.

To get the details.

```
    video get --all   # to get all videos
    video get -id QThadS3Soig   # to get specific video
```

To add the new video details.

```
    video add -id "Test" -title "Test" -url "Test" -imageurl "Test" -desc "Test"
```