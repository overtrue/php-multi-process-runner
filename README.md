# PHP Multi-Process Runner

PHP多进程执行工具

## Usage

下载pmr到本地

```shell
wget https://raw.githubusercontent.com/overtrue/php-multi-process-runner/master/pmr 
```

添加权限

```shell
sudo chmod +x ./pmr
```

语法：

```shell
./pmr 命令 最大进程数
```

多进行运行一个php文件示例：

```shell
./pmr "php test.php" 50
```
开启50个进程运行 `php test.php`

# License

MIT
