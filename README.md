only works with [Python 2.7](https://www.python.org/download/releases/2.7/) and it was tested with Node v6. There are two basic ways of installing : with Docker or without Docker.

If you already have a Python environment setup, install all of the server dependencies and start the server by typing the following in the terminal:

```bash
cd server
pip install -r requirements.txt
```

If it _did_ install tensorflow and magenta successfully, you can run the server by typing:

```bash
python server.py
```


## LICENSE

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
