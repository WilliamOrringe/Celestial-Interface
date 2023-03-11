# Celestial-Interface

This project aims to automate the process of creating videos and uploading them to YouTube, using Python programming language.

## Features

- Creating videos from images or videos with background music.
- Adding text overlays to the videos.
- Uploading the videos to a specified YouTube channel.

## Installation

1. Clone the repository to your local machine.
`git clone https://github.com/your_username/auto-video-maker.git`

2. Install the required dependencies.
`pip install -r requirements.txt`

3. Create a project in the Google Developers Console and obtain the `client_id.json` file for the project.

4. Authenticate the application by running the following command and follow the instructions to authorize the application with your Google account.
`python authentication.py`

## Usage

1. To create a video, run the following command.
`python create_video.py --images /path/to/images --audio /path/to/audio.mp3 --output /path/to/output.mp4`

2. To add text overlays to a video, run the following command.
`python add_text_overlay.py --video /path/to/video.mp4 --text "Sample Text" --output /path/to/output.mp4`

3. To upload a video to YouTube, run the following command.
`python upload_to_youtube.py --video /path/to/video.mp4 --title "Video Title" --description "Video Description" --category "22" --privacy "private"`

## Contributing

If you want to contribute to this project, please follow the steps below.

1. Fork the repository.

2. Clone the forked repository to your local machine.
`git clone https://github.com/your_username/auto-video-maker.git`

3. Create a new branch.
`git checkout -b feature/your_feature_name`

4. Make your changes and commit them.
`git commit -m "your commit message"`

5. Push the changes to your forked repository.
`git push origin feature/your_feature_name`

6. Create a pull request on the original repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
