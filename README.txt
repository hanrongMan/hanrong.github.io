Dimension by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Dimension, a fun little one-pager with modal-ized (is that a word?) "pages"
and a cool depth effect (click on a menu item to see what I mean). Simple, fully
responsive, and kitted out with all the usual pre-styled elements you'd expect.
Hope you dig it :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Responsive Tools (github.com/ajlkn/responsive-tools)


# 安装bundler，bundler通过gemfile文件来管理gem包
gem install  bundler

# 创建一个新的Jekyll项目，并命名为myblog
jekyll new myblog

# 进入myblog目录
cd myblog

# 在Jekyll自带的服务器上预览你的项目，默认的运行地址为http://localhost:4000
# bundle exec 表示在当前项目依赖的上下文环境中执行命令 jekyll serve
bundle exec jekyll serve

$ jekyll build
# => 当前文件夹中的内容将会生成到 ./_site 文件夹中。

$ jekyll build --destination <destination>
# => 当前文件夹中的内容将会生成到目标文件夹<destination>中。

$ jekyll build --source <source> --destination <destination>
# => 指定源文件夹<source>中的内容将会生成到目标文件夹<destination>中。

$ jekyll build --watch
# => 当前文件夹中的内容将会生成到 ./_site 文件夹中，
#    查看改变，并且自动再生成。

serve 指令将会自动监测变化，生成新的文件。想关闭这功能，你可以使用 jekyll serve --no-watch，这里还有其他几个参数：
jekyll serve --livereload相当于前端开发中自动刷新浏览器。
jekyll serve --incremental相当于模块热替换，只刷新更改的模块。
jekyll serve --detach 和jekyll serve命令相同，但是会脱离终端在后台运行，如果你想关闭服务器，可以使用kill -9 1234命令，"1234" 是进程号（PID）。如果你找不到进程号，那么就用ps aux | grep jekyll命令来查看，然后关闭服务器。

