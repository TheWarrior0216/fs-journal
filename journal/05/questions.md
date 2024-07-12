# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > | Create, Read, Update, Delete|

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > | Post, Get, Put, Delete |

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | Object-relational Mapping, A Schema |

04. Which two `HTTP` request types include a body?

  > | request and response |

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | Async, synchranous |

06. What are the three types of data relationships? Provide an example of each.

  > | One to One- Author to adress
   One to Many- Author to Comments
    Many to Many- Book to Author |

07. What is middleware?

  > | A place to check credentials, a gateway |

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | ANSWER HERE |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | async getWinter(request, response, next){
    const Winter = request.tag
    response.send(Winter)
  } |

10. What is a ***virtual property***?

  > | Something that needs to be populated and can not be changed |
