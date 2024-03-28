# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > it functions as an export/import system.

02. What is the difference between a `class` and an `interface`?

  > classes conain things, an interface is only a instance of a thing.

03. What is the method that returns an instance of a class, yet it has no return type?

  > I might be silly, but i dont think there is such a thing. I'll have to ask personally.

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

  > abstract

06. In the Car example what is `string` an indication of?

  > the return type of the function

07. In the Car example what is `abstract` preventing?

  > you can not make a new car; it can only be inherited

08. In a SQL table, what is the difference between information in a row and information in a column?

  > rows represent individual objects, columns represent given data types.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE characters (
    id INT NOT NULL primary key,
    name VARCHAR (255) NOT NULL,
    age VARCHAR (255),
    description VARCHAR (500)
  )

10. In SQL how can you query more than a single table? Provide an example.

  > just a comma should do. 
  SELECT * FROM accounts, bosses
