# DecorateIt

######NOTE: This is the version of DecorateIt without image processing. To view the version with image processing, [check out this repo](https://github.com/larissam/DecorateIt).

### DecorateIt is a web app that...
1. Lets you upload a photo or take one using the built-in photobooth (seen below):
![Photobooth](https://github.com/larissam/DecorateIt/blob/master/readmeimages/photobooth.png "Photobooth")

2. (Not activated in this version) Automatically enhances your photo by enlarging your eyes and smoothing your skin, as shown in the gif below:
![Image Processing](https://github.com/larissam/DecorateIt/blob/master/readmeimages/enlargeeyes.gif "Image Processing")

3. Lets you decorate your chosen photo using markers, brushes, and stamps:
![Editor](https://github.com/larissam/DecorateIt/blob/master/readmeimages/editor.png "Editor")

4. Lets you download, email, or save your decorated photo to your gallery:
![Gallery](https://github.com/larissam/DecorateIt/blob/master/readmeimages/gallery.png "Gallery")


### To get it running locally

1. Clone this repo
<code>$ git clone https://github.com/larissam/DecorateIt-NoImageProcessing.git </code>

2. Install dependencies
<code>$ pip install -r requirements.txt </code>

3. Run the app from the terminal
<code>$ python routes.py </code>


### Alternate versions
1. [DecorateIt with OpenCV](https://github.com/larissam/DecorateIt) - download this repo to run locally if you want to run DecorateIt with image processing.
2. DecorateIt on Heroku - In-progress version deployed on Heroku. CAVEATS: does not have photobooth or OpenCV functionality. Only supports jpgs and pngs. Needs security improvements. Only tested on Chrome version 39.0.2171.71 running OSX. 


### How it works

- Image editor was built using pure HTML5 Canvas and Javascript. Javascript uses the mouse's position on the canvas to determine where to draw. No plugins used.
- Photobooth was built using pure HTML5 canvas and Javascript. No plugins used.


### Stack
- Photo editor and photobooth: HTML5 Canvas, JavaScript, Python, HTML, CSS, Bootstrap
- Image processing, email handling, and database: Python, SQLite, SQLAlchemy, Flask-Mail
- Framework: Flask



