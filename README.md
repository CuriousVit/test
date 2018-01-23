# test
test

## collapsible markdown?

<details><summary>CLICK ME</summary>
<p>

#### yes, even hidden code blocks!

```python
print("hello world!")
```

</p>
</details>




##### Potential problems:

<details><summary>Git authentication fails after enabling 2FA</summary>
<p>
After 2FA is enabled there are a couple of scenarios where you need to enter a personal access token instead of a 2FA code and your GitHub password. For more information, see:
  
[Creating a personal access token for the command line.](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)
</p>
</details>

<details><summary>Create a new admin user in DB:</summary>
<p>
 
```
INSERT INTO users
(email, username, password, type, firstname, lastname, state, access, is_demo, department, system_account, editable_account)
VALUES
('vitali.kavaleuski+1@patientpop.com', 'vitali.kavaleuski+1', '$2y$10$mlLMjq2Qtv.uahfQWToaEehST3IAaat1DdMxHfMyAiUFJwa1aOmrO', 'INTERNAL', 'Name', 'Lastname', 'ACTIVE', 'ar1,aw1', 1, 'ADMIN', 0, 1);
```

</p>
</details>
