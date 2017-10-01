Solidity mapping might look similar to an associative array but it is not. It doesn't have indices.

It is very common to use mapping to store user addresses and their value. Eg

```
mapping (address => uint) Users;
```

How do you loop through the addresses since it doesn't have any indices?

