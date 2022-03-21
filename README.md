# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (actualAge){
  if (actualAge == 1){
    return {
      humanYears: actualAge,
      catYears: 15,
      dogYears: 15,
    }
  }

  if (actualAge == 2){
    return {
      humanYears: actualAge,
      catYears: 24,
      dogYears: 24,
    }
  }

  return {
    humanYears: actualAge,
    catYears: (actualAge - 2) * 4 + 24,
    dogYears: (actualAge - 2) * 5 + 24,
  }
}
```

| Input | Output |
| ----- | ------ |
|   1   |    { humanYears: 1, catYears: 15, dogYears: 15 } |
|   2   |    { humanYears: 2, catYears: 24, dogYears: 24 } | 
|   6   |    { humanYears: 6, catYears: 40, dogYears: 44 } | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes an input of age in human years and returns an output of what that age is in dog and cat years. Useful if you want to figure out how old your pet is in their respective years. My cat Lily is 40 in cat years.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
