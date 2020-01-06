# Software Engineering homework

__Gradle version 4.10+__

Build and Run

        gradle bootRun
        curl http://localhost:8080/?year=2017

Examples

        request: curl http://localhost:8080/?year=2017
        response: {"errorCode":200,"date":"13/09/17"}
  
        request: curl http://localhost:8080/?year=2020
        response: {"errorCode":200,"date":"12/09/20"}
        
        request: curl http://localhost:8080?year=0  
        response: {"errorCode":200, "date":"Incorrect year!"}
        