```sml
fun validPerms L p = 
    let
        val LL = perms L
    in
        filter p LL
    end
```

```sml
fun validPermsStaging L =
    let
        val LL = perms L
    in
        fn p => filter p LL
    end
```
