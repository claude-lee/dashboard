
Getting Started

1. Change your directory to mtas_tr_dashboard  and install required modules

$ cd mtas_tr_dashboard && npm install

2. Start the server!

$ dashing-js start

3. Have fun!

Point your browser at http://localhost:3030/

Every new Dashing project comes with sample widgets & sample dashboards for you to explore. The directory is setup as follows:

Assets ? All your images, fonts, and js/coffeescript libraries. Uses Sprockets Mincer.
Dashboards ? One .jade file for each dashboard that contains the layout for the widgets.
Jobs ? Your js/coffee jobs for fetching data (e.g for calling third party APIs like twitter). Name them \.job.js/*.job.coffee*
Lib ? Optional js/coffee files to help out your jobs.
Public ? Static files that you want to serve. A good place for a favicon or a custom 404 page.
Widgets ? All the html/css/coffee for individual widgets.
Run dashing-js from command line to find out what command line tools are available to you.

Deployment

dashing-js is setup to be easily deployed on a Joyent Node SmartMachine. This means that:

The version of Node is defined in package.json
The main script to run is server.js
The web server port is pulled from process.env.PORT
