# 适合于 PHP 开发的 devcontainer 配置

这是一个适合于 PHP 开发的 devcontainer 配置，其中包含了 PHP、Composer、Xdebug、PHPUnit、MariaDB、PhpMyAdmin 等工具。

## 使用方法

1. 安装 [Docker](https://www.docker.com/get-started) 和 [Visual Studio Code](https://code.visualstudio.com/)。
2. 安装 [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) 扩展。
3. 克隆本仓库。
4. 在 Visual Studio Code 中打开本仓库。
5. 点击左下角的 `><` 图标，选择 `Reopen in Container`。
6. 等待容器构建完成，即可开始 PHP 开发。

## 容器中的工具

- PHP 8.3
- Composer
- Xdebug
- PHPUnit
- MariaDB
- PhpMyAdmin

## 配置文件

- `.devcontainer/devcontainer.json`：容器配置文件。
- `.devcontainer/Dockerfile`：容器构建文件。
- `.devcontainer/docker-compose.yml`：容器编排文件。

## 注意事项

- 容器中的 PHP 配置文件在 `/usr/local/etc/php/` 文件夹下。里面有 `php.ini-development` 和 `php.ini-production` 两个配置文件。
- 容器中的 MariaDB 配置文件在 `/etc/mysql/` 文件夹下。