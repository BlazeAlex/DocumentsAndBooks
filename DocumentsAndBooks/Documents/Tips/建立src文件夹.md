1. 新建一个文件夹，为项目名。例如`TestSolution`。
2. 进入文件夹后，打开`cmd`后，定位到`TestSolution`文件夹，然后输入：

```
dotnet new sln

```

3. 接下来，创建一个名为`ClassLibrary`类库，类库需要包含`src`文件夹

```
dotnet new classlib -o src/ClassLibrary

```

4. 将类库添加到解决方案中：

```
dotnet sln add src/ClassLibrary

```

