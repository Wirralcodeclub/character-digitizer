#Character Digitizer - Wirral Code Club 09-19-25
hello@wirralcodeclub.org

A prototype that lets users photograph their character drawings with a standalone pc and connected camera, automatically uploads them to a storage backend, and provides a downloadable link or QR code.

- Camera capture on the PC.
- Upload to a remote web server.
- The web server stores the image and serves it over HTTP(S).
- PC receives the public URL back from the server.
- PC generates and displays a QR code with that URL for the user.

  Looks like python would be best for front end, using opencv library for image capture, sending images to a back end web server.
