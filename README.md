# AutoJs6 Runtime Kits

> **This is not an app.** To install AutoJs6, download an APK from [AutoJs6 Releases](https://github.com/SuperMonster003/AutoJs6/releases).
>
> **这里不是应用下载页.** 安装 AutoJs6 请到 [AutoJs6 Releases](https://github.com/SuperMonster003/AutoJs6/releases) 下载 APK.

This repository only stores `autojs6-runtime-kit-*.zip`, the build inputs of
[AutoJs6-Plugin-APK-Builder-Template](https://github.com/SuperMonster003/AutoJs6-Plugin-APK-Builder-Template).

- For every AutoJs6 tag, the `Release Runtime Kit` workflow of AutoJs6 uploads five kits
  (universal, arm64-v8a, armeabi-v7a, x86_64, x86) to the Release with the same tag here.
- It then notifies the template repository, which downloads and verifies the kits and publishes
  the signed plugin APKs to its own Release with the same tag.
- The zip files cannot be installed on a device. To pack scripts into an APK, install AutoJs6
  and then the APK Builder Template plugin from the AutoJs6 Plugin Center.

Releases here are written by automation. Please report problems in the
[AutoJs6 repository](https://github.com/SuperMonster003/AutoJs6/issues).

## 简体中文

本仓库只存放 `autojs6-runtime-kit-*.zip`, 它们是
[AutoJs6-Plugin-APK-Builder-Template](https://github.com/SuperMonster003/AutoJs6-Plugin-APK-Builder-Template) 插件的构建输入.

- AutoJs6 每推送一个版本标签, 其 `Release Runtime Kit` 工作流就把五个 Kit
  (universal, arm64-v8a, armeabi-v7a, x86_64, x86) 上传到本仓库的同名 Release.
- 随后通知模板仓库, 由它下载并校验这些 Kit, 再把签名后的插件 APK 发布到模板仓库的同名 Release.
- 这些 zip 不能安装到手机上. 需要把脚本打包成 APK 时, 请安装 AutoJs6,
  再从 AutoJs6 插件中心安装 APK Builder Template 插件.

本仓库的 Release 由自动化流程写入. 遇到问题请到 [AutoJs6 仓库](https://github.com/SuperMonster003/AutoJs6/issues) 反馈.
