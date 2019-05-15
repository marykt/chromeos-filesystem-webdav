[![Code Climate](https://codeclimate.com/github/yoichiro/chromeos-filesystem-webdav/badges/gpa.svg)](https://codeclimate.com/github/yoichiro/chromeos-filesystem-webdav)

# WebDAV File System

WebDAV File System provides you an ability to access to your WebDAV storage directly from the Files app.

<a target="_blank" href="https://chrome.google.com/webstore/detail/webdav-file-system/hmckflbfniicjijmdoffagjkpnjgbieh">
  Go to WebDAV File System page on Chrome WebStore
</a>

<img src="https://raw.githubusercontent.com/yoichiro/chromeos-filesystem-webdav/master/docs/screenshot.png">

## In my version

因为原作者长时间没有更新,而且我并不精通javascript.我尽量让这个项目能够使用。我做了以下更改（相比原版来说）
1.我编译使用的nodejs版本为（做了一些让编译通过的工作）
2.目前版本只能使用账号密码登录的方式（坚果云（https://www.jianguoyun.com）测试通过）

Because the original author has not updated for a long time, And I'm not proficient in javascript. I try to make this project available. So I made some changes (compared with the original version)

1. The version of nodejs that I used to compile is (I dose some work for compilation to pass)

2. Current versions can only use password login （(https://www.jianguoyun.com) test passed)

## How to build

```
$ git clone https://github.com/yoichiro/chromeos-filesystem-webdav.git
$ cd chromeos-filesystem-webdav
$ npm install
$ grunt
```

## Dependent libraries

* [Polymer](https://www.polymer-project.org/)
* [jQuery](http://jquery.com/)

## License

All files are licensed under the BSD license. See the LICENSE file for details.
All original source code is Copyright 2015 Yoichiro Tanaka.
