# flask_and_dropzone
Example code for using Flask with Dropzone to upload one or many files along with form data. I made this sample because I didn't see an example available that shows you this particular combination of things in a use case. 

My sample is based off of Miguel Grinberg's "[Handling File Uploads with Flask](https://blog.miguelgrinberg.com/post/handling-file-uploads-with-flask)" tutorial.

# What are Flask and Dropzone? 
Flask is a micro web framework that makes developing web applications easy. Dropzone is a JavaScript library that lets you create a drag n' drop zone where you can place files for upload. It's easy to style and does a lot of the work for you when it comes to handling uploads. 

By default, Dropzone uploads everything you drop immediately. That can be a bit of a pain point if you wanted Dropzone to wait for you to add all your files, or you wanted to be able to submit form data alongside your files. This code sample shows you how to disable the default setting for Dropzone, add your form data, then receive everything with your backend and process it. 
