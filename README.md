In main.js and restaurant_info.js insert your GOOGLE MAPS API KEY in the loadScript()  function (bottom of the files) in order for the app to retrieve the Maps. You may need to un-gzip both files to insert the Api key (read below).


The app contains both gzip and non gzip files. Allow the server to fetch gzip in order to obtain better performance. 

Every page in the app have inline CSS to optimize the Critical Rendering Path and improve perfomance.

The Audits folder contains lighthouse report: the html file is the report from lighthouse npm package , while the json file is the report from lighthouse running in the chrome dev tool.

