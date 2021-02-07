liveproject-scaffold-generator-handler
---

### Manning - liveProject - Scaffold Generator in Go - Web App Handler

We will create two web applications that will be generated by the command-line application.

One version of the code will be for an API backend-only web application. In other words, this will be a web application with no frontend.

The other version will be used to create a website. It will serve HTML, JavaScript, and cascading style sheets (CSS) files. Once you have the web applications ready, you will use Go templates to create a templated version of each.


This project is for the API Handler one


## Important notes

### XCode

Under MacOS you need to have XCode installed to use the net/http library

### 8080 port already in use

If the 8080 port is already in use the application as it was doesn't start, but it even doesn't give any error message.

We have extended the logic to capture such case.


### How to stop the server

On the terminal where the server has been started, enter ctrl-C
