# 书目清单及参考（网站，视频，教材，教程等）
   * 权威参考网站
      + [W3C - STANDARDS](https://www.w3.org/standards/)<br>
         >The World Wide Web Consortium (W3C) is an international community where Member organizations, a full-time staff, and the public work together to develop Web standards. Led by Web inventor and Director Tim Berners-Lee and CEO Jeffrey Jaffe, W3C's mission is to lead the Web to its full potential. Contact W3C for more information.
      + [HTML & CSS](https://www.w3.org/standards/webdesign/htmlcss) - 这个是W3C 关于HTML和CSS相关技术的权威解释<br>
         >HTML (the Hypertext Markup Language) and CSS (Cascading Style Sheets) are two of the core technologies for building Web pages. HTML provides the structure of the page, CSS the (visual and aural) layout, for a variety of devices. Along with graphics and scripting, HTML and CSS are the basis of building Web pages and Web Applications. Learn more below about:
   * 书目清单（优先级顺序）
      + []() - 的<br>

   * 其他参考
      - [Notes]() -- 这<br>

# html知识总览

   * :eight_pointed_black_star:关于 Encoding - 文件的编码格式，-- **需要学习的知识** --
      + Google Search
         1. how to convert file encoding with command line tool in windows site:stackoverflow.com
      + 参考
         - [How to Encode an Excel File to UTF-8 or UTF-16](https://help.surveygizmo.com/help/encode-an-excel-file-to-utf-8-or-utf-16)<br>
      + 转换与查询的方法
         - Linux
            + 参考
               1. [How to Convert Files to UTF-8 Encoding in Linux](https://www.tecmint.com/convert-files-to-utf-8-encoding-in-linux/)<br>
               2. [HowTo: Check and Change File Encoding In Linux](https://www.shellhacks.com/linux-check-change-file-encoding/)<br>
               3. [How to find encoding of a file via script on Linux?](https://stackoverflow.com/questions/805418/how-to-find-encoding-of-a-file-via-script-on-linux)<br>
            + 步骤与方法
               1， 查询文档的编码格式
               ```bash
                   $ file -i Car.java
               ```
               2. 转换（更改）编码格式
               ```bash
                   $ iconv option
                   $ iconv options -f from-encoding -t to-encoding inputfile(s) -o outputfile 
               ```
               >Where `-f` or `--from-code` means input encoding and `-t` or `--to-encoding` specifies output encoding.
                To list all known coded character sets, run the command below:
               3. 列可用编码清单
               ```bash
                   $ iconv -l
               ```
         - Windows
            + 参考
               1. [Get encoding of a file in Windows](https://stackoverflow.com/questions/3710374/get-encoding-of-a-file-in-windows)<br>
               2. [Control encoding of batch-created file](https://superuser.com/questions/1408312/control-encoding-of-batch-created-file/1408345) - 这个是批量更改文件属性的方法，关键是学习其中的方法<br>
               3. [Converting UTF-16 to UTF-8 using WideCharToMultiByte in C on Windows](https://stackoverflow.com/questions/57134511/converting-utf-16-to-utf-8-using-widechartomultibyte-in-c-on-windows) - 这个是用C语言的方法，也是学习其中的C语言的代码方法<br>
               4. [Convert from ANSI to UTF-8](https://stackoverflow.com/questions/31471087/convert-from-ansi-to-utf-8) - 这个是Python的方法<br>
               5. [Convert sources to UTF-8 without BOM](https://stackoverflow.com/questions/54534765/convert-sources-to-utf-8-without-bom) - 这个是用 Window PowerShell的 脚本方法，PowerShell是微软新开发的Window 10操作系统上用到的脚本 <br>
               5. [Keep Same Encoding With Set-Content Multiple Files in PowerShell](https://stackoverflow.com/questions/56133188/keep-same-encoding-with-set-content-multiple-files-in-powershell)<br>
               6. PowerShell的官方教程 及 与Encoding相关的内容
                  - [Understanding file encoding in VSCode and PowerShell](https://docs.microsoft.com/en-us/powershell/scripting/components/vscode/understanding-file-encoding?view=powershell-6)<br>
                  - [Set-Content](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.management/set-content?view=powershell-6)<br>
               7. [Changing PowerShell's default output encoding to UTF-8](https://stackoverflow.com/questions/40098771/changing-powershells-default-output-encoding-to-utf-8)<br>
               8. [HOW TO SOLVE UNICODE ENCODING ISSUES - WHAT IS ENCODING?](https://blog.invivoo.com/how-to-solve-unicode-encoding-issues/)<br>
               10. [WMIC command in batch outputting non UTF-8 text files](https://stackoverflow.com/questions/55310573/wmic-command-in-batch-outputting-non-utf-8-text-files)<br>
         - Mac OS
            + 参考
               1. [How to Determine File Encoding in Mac OS by Command Line](http://osxdaily.com/2017/09/02/determine-file-encoding-mac-command-line/)<br>
               2. []()<br>
# Sample
   * Google Search
      + html5 css3 sample site:github.com
