# 合并三方cyript
1. [mjcript](https://github.com/CoderMJLee/mjcript)
```sh
git clone https://github.com/CoderMJLee/mjcript.git /usr/lib/cycript0.9/com/codermjlee
```
mj的已经转到`start.cy`中，全小写。

2. [cycript-utils](https://github.com/Tyilo/cycript-utils)
```sh
git clone https://github.com/Tyilo/cycript-utils.git /usr/lib/cycript0.9/com/tyilo
```



在`start.cy`中添加`@import com.codermjlee.mjcript;`， `@import com.tyilo.utils;`

并把`start.cy`拖到iPhone的`/usr/lib/cycripty0.9`中


## 用法
```sh
# cycript -p name
@import start
```
