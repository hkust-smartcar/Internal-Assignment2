## Marking Scheme for Assignment 2

### Check Sequence

```C++
add v 123
add v 234
add v 345
add v
add v 123 445
add v x
chg (valid) 1
chg (valid)
chg (valid) x
chg (invalid) 1
del (valid)
del (valid) 234
del (invalid)
del *
```
### Marks

| Items                                    | Marks |
| ---------------------------------------- | ----- |
| Valid add                                | 1     |
| Invalid add (incorrect # of parameters)  | 0     |
| Invalid add (failed to convert int)      | 1     |
| Did not assume add_entry() must return true in parse_arg() | 1     |
| Valid chg                                | 1     |
| Invalid chg (incorrect # of parameters)  | 1     |
| Invalid chg (failed to convert int)      | 1     |
| Invalid chg (illegal address)            | 1     |
| Valid del                                | 1     |
| Invalid del (incorrect # of parameters)  | 0     |
| Invalid del (illegal address)            | 0     |
| del *                                    | 1     |
| No memory leak                           | 1     |

-1 for not following instructions of posting homework on GitHub.