1. Xcode：Creating a Git repository
2. Finder：顯示.git檔案資料夾
   * 打开Finder，找到项目存储的目录，在目录中，有一个.git的子目录，时Xcode为存储git源相关数据自动创建的。

   * 如果你看不到.git目录，你需要让隐藏的文件可见。具体做法就是打开一个Terminal窗口，输入以下命令

     * 对于OS X Mavericks 10.9:

       ```
       defaults write com.apple.finder AppleShowAllFiles TRUE
       ```

       对于以前的OS X版本，

       ```
       efaults write com.apple.Finder AppleShowAllFiles TRUE
       ```

       为了重启Finder应用，输入

       ```
       killall Finder
       ```
3. 


