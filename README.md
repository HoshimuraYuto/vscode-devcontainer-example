# vscode-devcontainer-example

Sample collection of development environment using devcontainer.

## How to use

1. Find the sample you want to use in the projects folder.

2. Clone git repository.

```bash
git clone --filter=blob:none --sparse https://github.com/HoshimuraYuto/vscode-devcontainer-example.git [folder name]
```

3. Move to cloned git repository directory.

```bash
cd [folder name]
```

4. Set the option for `sparse-checkout`.

```bash
git sparse-checkout set projects/[folder name you want to use]
```

5.  Move files to the current directory and delete any unnecessary folders.

```bash
mv projects/[folder name you want to use]/{*,.[^\.]*} . && rm -r projects
```

**If you run this command, all files will be replaced, including this README file.**

6. (optional) Reinitialize git repository.

```bash
rm -rf .git && git init
```

## License

This project is licensed under the MIT No Attribution License. See the [LICENSE](LICENSE) file for details.

## Author

- [Github](https://github.com/HoshimuraYuto)
- [Twitter](https://twitter.com/HoshimuraYuto)
- [Blog](https://sukiburo.jp/)
