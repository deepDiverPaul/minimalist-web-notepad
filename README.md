# Minimalist Web Notepad

[![Build Status](https://drone.app.onlineer.de/api/badges/deepDiverPaul/minimalist-web-notepad/status.svg)](https://drone.app.onlineer.de/deepDiverPaul/minimalist-web-notepad)

This is an open source clone of notepad.cc, which is now defunct.

forked from [pereorga/minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad)

## Installation

### Docker

Start the container:
```
docker run -itd --name minimalist-web-notepad -p 8080:80 onlineer/minimalist-web-notepad
```

Alternatively, docker-compose can also be used:
```
docker-compose up -d
```
open http://localhost:8080 to get started

#### Environment variables

`MWN_BASE_URL`    The base URL for redirection and assets. Defaults to ''.

`MWN_SAVE_PATH`   The path to save the notes to. Relative paths are relative to `index.php` location.

`MWN_ENCRYPTION`  Enable encryption when not empty.

`MWN_CRYPTO_SALT` Random static salt to use for encryption.


## Screenshots

![Firefox](https://orga.cat/sites/default/files/images/firefox.png)

![IE](https://orga.cat/sites/default/files/images/ie.png)

![Edge](https://orga.cat/sites/default/files/images/edge.png)

![Chrome Android](https://orga.cat/sites/default/files/images/android_chrome_dark.png)

![Firefox Android](https://orga.cat/sites/default/files/images/android_firefox.png)


## Copyright and license

Copyright 2012 Pere Orga <pere@orga.cat>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
