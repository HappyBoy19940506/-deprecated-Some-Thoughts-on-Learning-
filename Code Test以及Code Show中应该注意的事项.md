# Code Test以及Code Show中应该注意的事项

1. ​	Code Test 一定要现成写，他会查你 package.json里面的 webpack版本号 或者react版本号
2. 展示出你全部考虑的方面， 比如安全性、性能不要觉得没必要，比如 react-redux，就算用不着，也要展示。
3. 注意 File Constructions， 注意 Low coupling , High Conhesion. 不要乱放文件位置， 用不到的东西，也不要放。 用不到 tsx，就不要放 tsx的配置文件。
4. 文件命名要规范，有语义化，遵从行业规矩。始终全部用驼峰式。
5.  space用 空格 还是 tab，一定要 自始至终 统一！！！！
6. 语言一致，既然用tsx，就全程用tsx，不要又出现js。
7. jason包里面既然不用karma就不要出现karma，既然不用tslint就不要写tslint
8. 时刻注意MVC结构， service和view拆开，不要写在一个react function里面。
9. 然后show 学校项目？
   1. 不要说 是哪个学校哪门课的项目，直接说名字
   2. 后期不断加新东西，比如test， 做修改，比如file structure
   3. 最好是和 job description相符合的技术去做
   4. 放上链接
   5. 不要光用html css js，要用框架 和 sass
   6. 