# php

## How to use

1. Install [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers). You can learn how to use Dev Containers in the [official docs](https://code.visualstudio.com/docs/devcontainers/containers).
2. Run `Dev Containers: Reopen in Container` command from the command palette or quick actions Status bar item.

3. Type the following commands.

```bash
mkdir app && cd app
```

4. Create a `index.php` file and write the following.

```php
<h1><?= "Hello World!"; ?></h1>
```

5. Start development server.

```bash
php -S 0.0.0.0:8000
```

## License

This project is licensed under the MIT No Attribution License. See the [LICENSE](https://github.com/HoshimuraYuto/vscode-devcontainer-example/blob/main/LICENSE) file for details.
