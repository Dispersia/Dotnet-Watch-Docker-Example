# Dotnet-Watch-Docker-Example

 To run this example, just use
 ```console
 docker-compose up
 ```
 
 navigate to: http://localhost:5000/api/values
 
 make any change to a file (such as Controllers > Values, change a value), save, and refresh the browser, it will automatically rebuild.
 
 Want to debug a line? Add a breakpoint, hit F5, and choose the dotnet instance that is running your app from the dropdown.
 
  Tada! Debugging dotnet watch run inside a docker container :)
