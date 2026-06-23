# laserlemon/ansi-demo

```
[1;31merror[E0382][0m: [1mborrow of moved value: `x`[0m
  [34m-->[0m src/main.rs:4:20
   [34m|[0m
 [34m3 |[0m     let y = x;
   [34m|[0m             [33m-[0m [33mvalue moved here[0m
 [34m4 |[0m     println!("{}", x);
   [34m|[0m                    [31m^[0m [1;31mvalue borrowed here after move[0m
```
