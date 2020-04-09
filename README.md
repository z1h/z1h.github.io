# Z1H 语言教程

<script type="text/javascript">
	window.addEventListener('load', function(){
		[].slice.call(document.querySelectorAll('a')).forEach(function(e){
			switch (e.innerText) {
				case 'View project on\nGitHub':
					e.innerHTML = '<small>响应慢? 前往</small> 大陆站点';
					break;
				case 'View project on GitHub':
					e.innerHTML = '前往大陆站点';
					break;
				case 'Download\n.zip file':
					e.innerHTML = '<small>大陆站</small>下载';
					break;
				case 'Download\n.tar.gz file':
					e.innerHTML = '<small>Github站</small>下载';
					break;
				case 'GitHub Pages':
					e.parentElement.style.display = "none";
					break;
			}
		});
	});
</script>
<div style="display: flex; flex-direction: row;">
	<img src="/favicon.ico" alt="logo" height="200" />
	<div style="margin-left: 16px;">
<p>Z1H 是一门跨平台编程语言，它能让构造简单、可靠且高效的软件变得容易。</p>
<p>Z1H是从2019年国庆期间由曾威人开发，后来张琪也加入了开发，并最终于2020年对外开放，并发布了v1.0.0稳定版本, 包含<strong>Windows、mac OS、Linux、Android、iOS、WebAssembly、树莓派</strong>等平台的发行版。</p>
	</div>
</div>


## Z1H 语言特色

- 简洁、快速、安全
- 并行、有趣、灵活
- 跨平台, 支持几乎所有的服务器、PC、移动设备系统, 以及部分IoT系统
- 语法由诸多其他语言发展而来, 包括Go、Java、JavaScript、Python等等
- 解释器由Go实现(Rust版本正在开发中), 确保了高效、支持高并发
- 支持所有Go的系统标准库
- 支持所有用Go开发的第三方库

## Z1H 语言用途

Z1H 语言被设计成一门主要应用于搭载 Web 服务器，存储集群或类似用途的巨型中央服务器的系统编程语言。

对初级程序员而言，是一种非常容易上手且功能强大的语言，它支持广泛的应用程序开发，从简单的文字处理到http服务再到游戏。

对于许多领域而言，Z1H 语言无疑比大多数其它语言有着更高的开发效率。它提供了灵活的开发语法以及海量并行的支持，这尤其对于想要快速开发http服务后端的团队和个人而言是再好不过了。

## 第一个 Z1H 程序

接下来我们来编写第一个 Z1H 程序 hello.z1h（Z1H 语言源文件的扩展是 .z1h），代码如下：

```
print("Hello World!")
```

要执行 Z1H 语言代码可以使用 **z1h -run** 命令。

执行以上代码输出:

```
$ z1h -run hello.z1h 
"Hello World!"
```

## 下载和更多教程


[前往大陆站点](https://z1h.zwei.ren/)


## HTTP服务

如果你已经有其它语言的开发经验, 建议直接前往[进阶-HTTP服务](https://z1h.zwei.ren/doc/020.html)体验Z1H开发HTTP后端服务的便利
