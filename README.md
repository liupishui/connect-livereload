# connect-livereload
字符替换
livereload执行过程中，字符替换
在index.js第119行后追加如下代码

        var lpslib=require('lpslib');
        body=lpslib.replaceFileWithStr(body,opt.options.base[0]);

