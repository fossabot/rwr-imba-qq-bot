# 服务器相关命令

## servers

### 用途

根据 SERVERS_MATCH_REGEX 筛选服务器, 查询服务器信息并生成图片输出

### 环境变量

-   SERVERS_MATCH_REGEX: 用于匹配服务器的正则表达式，用于 `servers` 命令的过滤

### 注册的指令

-   servers: 根据 SERVERS_MATCH_REGEX 筛选服务器, 查询服务器信息并生成图片输出
-   s: servers 的别名

## whereis

### 用途

根据 SERVERS_MATCH_REGEX 筛选服务器, 寻找玩家所在服务器并生成图片输出

### 环境变量

-   SERVERS_MATCH_REGEX: 用于匹配服务器的正则表达式，用于 `whereis` 命令的过滤

### 注册的指令

-   whereis: 查询玩家所在服务器(根据 `SERVERS_MATCH_REGEX` 过滤)并生成图片输出
-   w: whereis 的别名

## analytics

### 用途

根据 SERVERS_MATCH_REGEX 筛选服务器, 查询服务器玩家统计信息并生成图片输出

### 环境变量

-   SERVERS_MATCH_REGEX: 用于匹配服务器的正则表达式，用于 `analytics` 命令的过滤

### 注册的指令

- analytics: 根据 SERVERS_MATCH_REGEX 筛选服务器, 查询服务器玩家统计信息并生成图片输出
- a: analytics 的别名
