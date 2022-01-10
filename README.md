# Gallery
Created By DEV KIM on 31-12-2021
# Description
A personal gallery is a simple photo gallery web application to showcase beautiful pictures and designs. Users get to view photos updated by the site admin. Users can see photos based on the location, by clicking on the listed locations in the menu. They can also copy the link to a photo to paste at their discretion. The search function will search photos based on the categories.
# Screenshots

![my screenshot](https://media-exp1.licdn.com/dms/image/C4E22AQEDVEPoAmNJtA/feedshare-shrink_800/0/1641826249925?e=1644451200&v=beta&t=cYhOEOSmiabqtjcn-_AT3UR8iFV1zxKf0Lma4mPS0X4)
![my screenshot](https://media-exp1.licdn.com/dms/image/C4E22AQGZ7PKe1QsK4g/feedshare-shrink_800/0/1641826284441?e=1644451200&v=beta&t=Yrq-wUThLH_0V7NQRKM2kflNJ5hGuv2s4YUSWKQwPLg)
![my screenshot](https://media-exp1.licdn.com/dms/image/C4E22AQFGbh-_rJ6TFw/feedshare-shrink_800/0/1641826310224?e=1644451200&v=beta&t=t5e8wCzwv1MxP2AtOTfmiySwa7nLyJTeGZjT4gFDT0k)

# Setup Requirements
Git
Web-browser or your choice
Github
Django
Pip
Python 3.8
PostgreSQL
Cloudinary (for image upload)
   - CLOUD_NAME 
   - API_KEY
   - API_SECRET
# Setup Installation
Copy the github repository url
Clone to your computer
Open terminal and navigate to the directory of the project you just cloned to your computer
Run the following command to start the server using virtual environment
python3.8 -m venv --without-pip virtual
To activate the virtual environment
source virtual/bin/activate
curl https://bootstrap.pypa.io/get-pip.py | python
pip install -r requirements.txt
To copy .env.example to .env
cp .env.example .env
Edit the .env file and replace the values with your own Cloudinary credentials and database credentials

To run the server

python manage.py runserver

Open the browser and navigate to http://127.0.0.1:8000/ to see the application in action
# Technologies Used
The following languages have been used on this project:

HTML
CSS
Bootstrap
Python
Django
PostgreSQL

# Known Bugs
So far so good there are no bugs related to this project 😎

# Support and contact details 🙂
To make a contribution to the code used or any suggestions you can click on the contact link and email me your suggestions.

Email: malcomchege0582@gmail.com
Phone: +254793511825
# License
Copyright (c) 2021 Moringa school

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files , to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
