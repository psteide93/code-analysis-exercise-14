# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

| Input | Output |
| ----- | ------ |
| user = {userName: "John", isActive: true }      | "Welcome back, John | 
|  user = {userName: "Sara", isActive: false }    |"Hey Sara Would you like to renew your subscription" |

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This function will determine if the user is active or not and will display a message on the screen accordingly, interpolationg the user's name.
</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
