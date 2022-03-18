# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input | Output |
| ------------------------ | ----------------------- |
|    Shawn, Cannon, 28     | Shawn Cannon 28         | 
|    Allison, Cannon, 26   | Allison Cannon 26       | 
|    Clyde, Galavant, 6    |  Clyde Galavant 6       | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes 3 inputs; someones first name (value:firstName), their last name (value:lastName, and age(value:age) and creates an object from them with the argument of person. it then runs a return which will feed that information into a single value to create simple orginizatiobn of data. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
