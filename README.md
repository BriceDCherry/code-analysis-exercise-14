# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
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

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
|user: "bossybrice", isActive: (true)          | 'Welcome back, bossybrice!'       | 
|user: "merrymeredith", isActive: (false)      | 'Hey merrymeredith! Would you like to renew your subscription?'      | 
|user: "dustydavid", isActive: (true)          | 'Welcome back, dustydavid!'       | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This function enters a name and an active status, returns a welcome back message else it returns a renew subscription message based on if active status is true or false</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
