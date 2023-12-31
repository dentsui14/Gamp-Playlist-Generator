Download the data file here: https://drive.google.com/file/d/18i50nuVmmhOKDyQ2d9G-Spqlh76UfI7n/view?usp=sharing
Place it in the api folder.

# Getting Started on the Server Side
If you are using windows, you may need to use MINGW/Git Bash
1. Set up a Python virtual environment and install the required packages by running the setup script:
```shell
chmod +x setup.sh
./setup.sh
```

2. Start up the virtual environment
```shell
source .venv/bin/activate
```

2. Boot up the server by running the main script
```bash
python main.py
```

3. You should now have a python server running in the client if you navigate to port 8000. This port will make calls to port 8000 which you just set up to host the server.

4. If you run in to any CORS issues, restart your browser completely as caching might mess things up.

5. When you are done, deactivate the venv
```bash
deactivate
```
