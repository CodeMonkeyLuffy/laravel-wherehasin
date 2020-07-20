<div align="center">

# Laravel whereHasIn

</div>

`Laravel whereHasIn`是一个可以提升`Laravel ORM`关联关系查询性能的扩展包，可以替代`Laravel ORM`中的`whereHas`以及`whereHasMorphIn`查询方法。


## 环境

- PHP >= 7
- laravel >= 5.5


## 安装

```bash
composer require CodeMonkeyLuffy/laravel-wherehasin
```

### 简介

`Laravel`的关联关系查询`whereHas`在日常开发中给我们带来了极大的便利，但是在主表数据量比较多的时候会有比较严重的性能问题，主要是因为`whereHas`用了`where exists (select * ...)`这种方式去查询关联数据。

## License
[The MIT License (MIT)](LICENSE).
