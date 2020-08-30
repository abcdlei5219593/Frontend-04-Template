学习笔记

退出双层for循环
```
outer: for (let i = 0; i < 3; i++) {
  for (let j = 0; j < 3; j++) {
    if (condition) {
      break outer;
    }
  }
}
```