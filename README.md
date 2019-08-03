# PUT Endpoints Functionality Study

<br>

## What is the PUT Endpoints Functionality Study?
The "PUT Endpoints Functionality Study" demonstrates the basic functionalities of PUT requests, which allow the user to update existing information that exists on the server or database.

<br>

In an express application, to handle a PUT request, you would call the app object (note the use of cond app = require('express') ) with the POST method.  Put requests need to have the id of the item, (in this case) jsonParser, and the request response object.  Then you call List.update with the updated information.  

```JavaScript

app.put('/list/:id', jsonParser, (req, res) => {                                                                                    
  console.log(`Updating list item \`${req.params.id}\``);                                
  List.update({                                                                           
    id: req.params.id,
    name: req.body.name,
    budget: req.body.price
  });
  res.status(204).end();
});

```


<br>

## Does PUT Endpoints Functionality Study feature commentary?
Yes! The PUT Endpoints Functionality Study features commentary in the server.js file to show the structural context and implementation of POST endpoint functionality.  In addition, I also provide a Process text file that gives a good outline of the implementation process. 

<br>

## What are the key features of the PUT Endpoints Functionality Study?
Since this study is ongoing, basic functionalities are covered first and more advanced features are added or will be added in the future.  I divided this particular study into different branches covering different aspects of basic node servers, which i list below:


| **Features:**                            | **Feature Notes:**                             |
| ---------------------------------------- | ----------------------------------------------|
| PUT request to localhost:8080/shopping-list/:id      | This POST request will update the item addressed        |



<br>

## Screenshots
![put1](https://user-images.githubusercontent.com/37447586/62414925-e6200e00-b5d6-11e9-9eb1-f667440b5c6a.png)
![put2](https://user-images.githubusercontent.com/37447586/62414926-e6200e00-b5d6-11e9-84a5-f973646430b1.png)
![put3](https://user-images.githubusercontent.com/37447586/62414927-e6200e00-b5d6-11e9-8bd9-5aa2b5d73e6a.png)
