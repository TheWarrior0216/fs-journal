# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | It allows us to use other properties and bring it in to other classes |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | It inherits everything that is supposed to be for example if you have it set to private then it won't inherit all members, however it will grab it if it is public |

3. How does ***accessibility*** affect inheritance?

  > | Depending on what different functions are affect the different way it inherits if it is private than you cant use that function. |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | Primary key is the main identifier for the table, usually on the Id. Foreign key targets a specific id on your table and then it can be used to look outwards. |

5. What is an ***alias***?

  > | A term in sql that gives a temporary name|

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > | JOIN patients ON patient_doctors.patientId = patients.id 
  Where patients.doctorId = patient_doctors.doctorId |
