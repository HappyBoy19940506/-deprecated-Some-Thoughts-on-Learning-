# Code Test以及Code Show中应该注意的事项

1. ​	Code Test 一定要现成写，他会查你 package.json里面的 webpack版本号 或者react版本号
2. 展示出你全部考虑的方面， 比如安全性、性能不要觉得没必要，比如 react-redux，就算用不着，也要展示。
3. 注意 File Constructions， 注意 Low coupling , High Conhesion. 不要乱放文件位置， 用不到的东西，也不要放， 用不到 tsx，就不要放 tsx的配置文件。
4. 文件命名要规范，遵从行业规矩。
5.  space用 空格 还是 tab，一定要 自始至终 统一！！！！
6. 语言一致，既然用tsx，就全程用tsx，不要又出现js
7. 