# Challenge 0

## Challenge 0.a [1 Point]

In the current application, you may have noticed that at incorrect `login` attempts,  the system exposes too much information. For example, the current system displays the below message on the following scenario when the user email is not found.

| Scenario      |  |
| ----------- | ----------- |
| If user email is not existing, system shows message `User Not Found`      | [Challenge 0](./images/0a.png)      |


## Challenge 0.b [1 Point]

It also displays the below message on the following scenario when the password is not matched with the entered email.

| Scenario      |  |
| ----------- | ----------- |
| If user email does exists but the password is incorrect, system shows the message `Password Mismatch`   | [Challenge 0](./images/0b.png)        |

This is a bad security practice, as hackers will be able to verify if an user account is existing by simply testing around the system. Your task is to fix this by ensuring in both above scenarios, the system shows the exact same message `User authentication failed`.

Once these are completed, first two tests in `challenge0.test` should succeed. You can verify that by running the the command `npm test`.


## Challenge 0.c [1 Point]

Currently, the system displays a welcome message after successful authentication. The welcome message should include the user's firstname and the right top nav bar should include the users first and last names. 

| Scenario      |  |
| ----------- | ----------- |
| Welcome message displays `Welcome undefined` and Top nav bar shows `undefined undefined`  | [Challenge 0](./images/0c.png)         |

Your task is to retrieve the user's firstname and lastname from the backend after successful authentication. Then the firstanme will appear in the welcome message and both firstname and lastname will appear in the right hand side of the top nav bar.