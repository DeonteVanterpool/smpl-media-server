# smpl-media-server

A planned C++ media server using [cpp-httplib](https://github.com/yhirose/cpp-httplib).
It is intended to make media easy to embed in other projects using an iframe.

## How it works

The server is intended to provide a page for a specific media ID. The page
contains only the media itself, so it can be displayed in an iframe without
additional navigation or surrounding content:

- Videos appear in a `<video>` element.
- Audio appears in an `<audio>` element.
- Images appear in an `<img>` element.

The planned supported formats are MP3, MP4, PNG, and JPG. Uploads will require
username and password authentication.

## Status

This repository currently contains the project plan only. The server,
endpoints, and upload functionality have not yet been implemented.

## License

This project is licensed under the [MIT License](LICENSE).
