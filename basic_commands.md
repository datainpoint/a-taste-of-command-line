# 約維安計畫：第二週

> 初嘗命令列的滋味。

## 基礎命令一覽

首先，我們將這篇文章會介紹的基礎命令全數列出：

```
pwd                      # print working directory
mkdir folder_name        # make directory
ls                       # list directory and file
cd folder_name           # changing directory
touch file_name          # create file
mv file_name file_name   # move file
cp file_name file_name   # copy file
rm file_name file_name   # remove file
rm -r folder_name        # remove folder
clear                    # clear command line, ctrl-L
# up-arrow / down-arrow for history commands
# tab for auto-completion
# ctrl-C to stop execution
```

### 印出工作目錄的命令

`pwd`（print working directory）是印出工作目錄的命令，Jupyter 星球預設的起始工作目錄就是所謂的「家目錄」，也就是 /home/jovyan。

### 創造資料夾的命令
`mkdir folder_name`（make directory）是創造資料夾的命令，執行時必須告知新資料夾的名稱。

### 將目前所在工作目錄中的資料夾與檔案都列出來的命令

`ls`（list）是將目前所在工作目錄中的資料夾與檔案都列出來的命令。

### 更換工作目錄的命令

`cd folder_name`（change directory）是更換工作目錄的命令。

在使用 cd 命令更換工作目錄時，我們能夠使用 `cd ..` 表示更換至上一層，`cd ../..` 表示向上更換兩層。同理 `ls ..` 表示列出上一層的資料夾與檔案，`ls ../..` 表示列出向上兩層的資料夾與檔案。

在任何目錄下若是想要切換至特殊工作目錄（例如家目錄 `/home/jovyan` 或者根目錄 `/`）可以直接指定這兩個目錄的名稱：

- 家目錄的名稱：`~`
- 根目錄的名稱：`/`

因此使用 `cd ~` 可以從任何目錄直接更換到家目錄，使用 `cd /` 可以從任何目錄直接更換到根目錄。

### 創造檔案的命令

`touch file_name` 是創造檔案的命令，執行時必須要告知新檔案的名稱以及副檔名。

### 移動檔案的命令

`mv file_name file_name`（move）是移動檔案的命令，執行時必須告知欲移動的檔案名稱、以及移動後更換的檔案名稱，因此也能夠用來進行檔案的重新命名。

### 複製檔案的命令

`cp file_name filename`（copy）是複製檔案的命令，執行時必須告知欲複製的檔案名稱、以及複製後的檔案名稱。

### 移除檔案的命令

`rm file_name`（remove）是移除檔案的命令，執行時必須要告知欲移除檔案的名稱以及副檔名。

### 移除資料夾的命令

在移除檔案的命令 `rm` 加入參數 `-r` 就變成能夠移除資料夾的命令，執行時必須要告知欲移除資料夾的名稱。

### 清除目前畫面的命令

clear 是清除命令列目前畫面的命令，也可以用快捷鍵 Ctrl-L 來達成相同目的。

除了前述這些基礎的命令，在使用命令列的時候也能善用一些快捷鍵加快效率，像是透過「上」與「下」的箭頭瀏覽曾經執行過的指令、透過 Tab 鍵自動完成供使用者快速輸入以及透過 Ctrl-C 來中斷執行中的應用程式等。