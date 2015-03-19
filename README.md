# PHP Multi-process Runner

基于 PHP 拓展 [PCNTL](http://php.net/manual/zh/book.pcntl.php) 的多进程执行工具。

## Usage

下载 pmr 到本地

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

多进程运行一个 php 文件示例：

```shell
./pmr "php test.php" 50
```
开启50个进程运行 `php test.php`

## License

MIT
