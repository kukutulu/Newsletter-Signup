1. run static file using express.static("folder_include_file_name")
and then, in html file or elsewhere, whenever you need to call these files,
just call it, do NOT include "folder_include_file_name" in the path

2. the Procfile is the file that include the command so that the heroku server
know which command you use to run your app 

