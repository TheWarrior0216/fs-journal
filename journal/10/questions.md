# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | to allow access to other files |

02. What is the difference between a `class` and an `interface`?

  > | Instructions given to a class? |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | Void |

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > | The "public" |

06. In the Car example what is `string` an indication of?

  > | A typing for the return|

07. In the Car example what is `abstract` preventing?

  > | from being used unless its inherited |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | The rows hold all the information for each item whereas the column hold the same data |

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > | CREATE TABLE 
  characters(
    id INT NOT NULL AUTO_INCREMENT PRIMARY_KEY,
    name VARCHAR(255) NOT NULL, 
    age VARCHAR(255) NOT NULL, 
    description VARCHAR(255) NOT NULL, 
  ) |

10. In SQL how can you query more than a single table? Provide an example.

  > | Select 
  accounts.*
  characters.*
  FROM
  accounts |
