# RelativeCopyTool
 
本アプリケーションはルートフォルダから目的のファイルまでの階層を維持した状態でフォルダとファイルをコピーするツールです。  
This application is a tool to copy folders and files while maintaining the hierarchy from the root folder to the target file.  
 
# DAMO
 
以下のようなファイル構造があります。  
The file structure is as follows  

└── Data/    
　　　　├── A/  
　　　　│　　└── B/   
　　　　│　　　　└── C/  
　　　　│　　　　　　└── SampleFile.txt  
　　　　└── CopyTarget

ルートフォルダを【A】  
コピーするファイルを【SampleFile.txt】  
コピー先を【CopyTarget】として実行します。  

すると以下のようになります。  

Root folder is 【A】.  
Copy file as 【SampleFile.txt】.  
Copy the file to be copied to 【CopyTarget】.  
The following will then be shown.  


└── Data/  
　　├── A/  
　　│　　└── B/  
　　│　　　　└── C/  
　　│　　　　　　└── SampleFile.txt  
　　└── CopyTarget/  
　　　　　└── B/  
　　　　　　　└── C/  
　　　　　　　　　└── SampleFile.txt  

このように間の階層を維持した状態でコピーを作成できます。  
In this way, copies can be made while maintaining the hierarchy between them.

 
# Requirement
 
Windows10,Windows11の64bitでの動作を確認しています。  
We have confirmed the operation on 64-bit Windows 10 and Windows 11.
 
 
# Usage

ツールを開くと上からRoot,CopyFile,TargetFileを指定できます。  
When you open the tool, you can specify Root, CopyFile, and TargetFile from the top.

ファイルやフォルダの指定は右の選択ボタンを押して選択する方法や、ドラッグアンドドロップで設定することもできます。  
Files and folders can be specified by pressing the selection button on the right, or by drag-and-drop.

チェックボックスを有効化するとコピーが成功したときにコピー先のフォルダを自動的に開くことができます。  
Activate the checkbox to automatically open the destination folder upon successful copying.

以上の設定が完了した状態で、実行を押すとポップアップが表示され成功もしくはエラーを表示します。  
With the above settings completed, pressing Run will display a pop-up window indicating success or error.

 
# Note
> [!TIP]
> このアプリケーションは、ネットワークを利用せずにオフラインで使用することができます。
> This application can be used offline without network access.

> [!WARNING]
> このアプリケーションは、ユーザーのプライバシーを侵害することはありません。
> 個人情報の収集や外部サーバーへのデータ送信は一切行いません。
>
> This application does not violate the privacy of its users.
> It does not collect any personal information or transmit any data to external servers.

> [!CAUTION]
> このアプリケーションを使用することによって、ファイルやフォルダ、PCが破損した場合でも、開発者は一切の責任を負いかねます。
本アプリケーションの使用は、すべて自己責任で行ってください。
> 
> The developer assumes no responsibility for any damage to files, folders, or PCs that may result from the use of this application.
Use of this application is entirely at your own risk.

 
# Author
 
* Namiton
* X [@koituwasugee](https://x.com/koituwasugee)
 
# License
 
RelativeCopyTool is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
 
