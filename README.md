# youtube-downloader
downloads youtube videos

# get node.js and python and C# and the dev kit then To run ffmpeg you need chocolatey and then run this on the terminal of windows. choco install ffmpeg use the url function for ffmpeg on sites like twitch or vimeo to have protocols like HLS (.m3u8) or DASH (.mpd). Then use the docker hub application and extension to get it to work type in vs code. docker pull jrottenberg/ffmpeg This will do the trick but if you need a converter try using https://github.com/SevenbytesSoftware/SevenConverter

visual studio code and it will work like a charm add your email and username to setup.py
To run ffmpeg you need chocolatey and then run this on the terminal of windows. choco install ffmpeg
use the url function for ffmpeg on sites like twitch or vimeo to have protocols like HLS (.m3u8) or DASH (.mpd).
Then use the docker hub application and extension to get it to work type in vs code. docker pull jrottenberg/ffmpeg
This will do the trick but if you need a converter try using https://github.com/SevenbytesSoftware/SevenConverter

# Locate this section in cipher.py
function_patterns = [
    r'a\.[a-zA-Z]+\s*&&\s*\([a-zA-Z]+\s*=\s*a\.get\("n"\)\)\s*&&.*?||\s*([a-zA-Z]+)',
    # Add other patterns if necessary
]

# Ensure the rest of the code remains unchanged
you need wsl for the umbuntu virtual environment for windows https://code.visualstudio.com/docs/remote/wsl-tutorial
doesn't work install git bash and run this in it for it to work wsl --install
run umbuntu command like these you will have umbuntu after you run the command for git bash sudo apt update 
and sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev wget libbz2-dev
then run this after you do that sudo apt install python3.11 and wget https://www.python.org/ftp/python/3.11.3/Python-3.11.3.tgz
then run this in umbuntu command promt curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
then run these too in umbuntu command promt nvm install node and nvm use node
then run this too in umbuntu command promt curl -L -o ffmpeg.zip https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-full.7z
run this before you run the umbuntu command npm install -g npm
umbuntu command npm install -g npm@latest
umbuntu command npm install -g npm-check-updates
umbuntu command python -m pip install SomePackage
a few commands to become root user in umbuntu are sudo -i and sudo su
# and the rest are for visual studio
npm install --no-bin-links
icacls setup.py /grant *S-1-1-0:RX
pip install -r requirements.txt -r requirements-dev.txt -r requirements-interactive.txt
pip install .[dev,interactive]
python setup.py install
python setup.py install_npm
python setup.py sdist
python setup.py bdist_wheel
# then run these commands to use the downloader
# python download_youtube_yt_dlp.py
# python index.py
# python app.py
# ffmpeg -i "http://example.com/video.mp4" output.mp3
# ffmpeg -i "C:\path\to\your file.mp4" output.mp3
# Lifecycle scripts in package.json are predefined script names that npm executes automatically at specific stages during the lifecycle of a package. Here are some common lifecycle scripts you can define: npm init -y then if it doesn't work make sure it will by running npm run check && npm run download && npm run
