<p align="center">
    <img src=https://gw.alipayobjects.com/zos/k/fa/logo-modified.png width=138/>
</p>
<h1 align="center">轻松构建轻量级多端桌面应用</h1>
<p align="center"><strong>Turn any webpage into a desktop app with Rust <em>with ease</em>.</strong></p>


## 使用教程

- 🎐 Fork 我的pake项目
- 🚀 前往 actions 页面启用 GitHub actions 可以通过链接https://github.com/[你的用户名]/Pake/settings/actions快速进入设置。路径：进入项目settings-Actions-Genneral-Workflow permissions,勾选"Read and write permissions"与“Allow GitHub Actions to create and approve pull requests”。
- 📦 上传图标
  - 上传.ico 和.png 文件至/src-tauri/png目录下（打包windows/linux是需要的）
    先制png，这里一键转换ico：https://www.aconvert.com/cn/icon/png-to-ico/
  	文件名称		说明
  	app_32.ico	32*32 的 ico 图标
  	app_256.ico	256*256 的 ico 图标
  	app_512.png	512*512 的 png 图片
	
  - 上传.icns 文件至/src-tauri/icons目录下（必须，打包mac应用）
	  app.icns	的 icns 图标
    先制png，这里一键转换icns：https://www.alltoall.net/png_icns/

- 👻 最后进入actions-Build Single Popular App-Run workflow进行打包，最后在项目底部Artifacts进行下载

## Support
技术支持：少年与梦 -》接单封装客户端 微信：sn5dial
