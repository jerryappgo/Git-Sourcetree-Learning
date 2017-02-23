參考教學：

* [\[iOS\]\[Swift\]在Xcode中使用Git进行源码版本控制](http://www.jianshu.com/p/49606a737c42)
* \[iOS\]\[Swift\]在Xcode中使用Git进行源码版本控制　http://www.jianshu.com/p/49606a737c42

---

1. **Xcode：Creating a Git repository**
   * 如果忘了用，也可以用Terminal新建：
     * 打开Terminal终端，进入项目的目录位置。`cd 项目位置`

     * `cd documents/Git_Demo`

     * 然后初始化git源：`git init`

     * 这时候.git文件夹已经被创建了，但是还是一个空的源，我们要将项目现有的内容加入其中：`git add .`  
       （切记这不要忽略了add后面的“.”）

     * 最后输入：`git commit -m 'Initial commit'`
2.  **Finder：顯示（被隱藏）.git檔案資料夾**

   * 打开Finder，找到项目存储的目录，在目录中，有一个.git的子目录，时Xcode为存储git源相关数据自动创建的。

   * 如果你看不到.git目录，你需要让隐藏的文件可见。具体做法就是打开一个Terminal窗口，输入以下命令

     * 对于OS X Mavericks 10.9:

       ```
       defaults write com.apple.finder AppleShowAllFiles TRUE
       ```

       对于以前的OS X版本，

       ```
       efaults write com.apple.Finder AppleShowAllFiles TRUE
       ```

       为了重启Finder应用，输入

       ```
       killall Finder
       ```

3. 


