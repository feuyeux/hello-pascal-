
### 提示词

```text
编写一个汉诺塔游戏并使用 Free Pascal Compiler (fpc) 进行编译和执行，我们可以按照以下步骤进行：

1. 创建一个 Pascal 源文件来实现汉诺塔游戏。
2. 使用 fpc 编译该源文件。
3. 执行生成的可执行文件。
```

### 安装 Free Pascal Compiler

```sh
brew install fpc  
```

### 编译和运行

1. 打开终端并导航到包含 `hanoi.pas` 文件的目录：
    ```sh
    cd hello-pascal
    ```

2. 使用 fpc 编译 `hanoi.pas` 文件：
    ```sh
    fpc hanoi.pas
    ```

3. 编译成功后，将生成一个名为 `hanoi` 的可执行文件。运行该可执行文件：
    ```sh
    ./hanoi
    ```
