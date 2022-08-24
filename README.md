# change-target-url
A few solutions on how you can change the target endpoint url in the proxy target endpoint request flow

## Instructions

In this repo are 3 zip files; hello-world-ctu-am, hello-world-ctu-js, and hello-world-ctu-am-js. Each one provides a different means to solve the same problem, changing the target endpoint url. hello-world-ctu-am updates the target.url using only an AssignMessage policy. hello-world-ctu-js updates the target.url using only a JavaScript policy. hello-world-ctu-js-am updates the target.url using a JavaScript policy to set a url variable and an AssignMessage policy to apply the target.url change using a reference to the variable created in the JavaScript file.

To use a zip file download it to your local system, navigate to Apigee Dashboard > API Proxies > Create New > Upload Proxy Bundle, and upload the zip file there.