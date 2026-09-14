# 上传GitHub

本说明适用于首次通过网页上传。建议仓库名：ipo-financial-pr。

## 1. 下载并解压

将发布包解压，打开ipo-financial-pr文件夹。里面应直接看到SKILL.md、README.md、LICENSE及references、agents、assets、docs文件夹。

## 2. 创建公开仓库

登录GitHub并打开[新建仓库](https://github.com/new)。

- Repository name：ipo-financial-pr。
- Description：A股与港股IPO财经公关Skill，支持内部PR与顾问模式。
- Visibility：Public。
- 本发布包已包含README和LICENSE，创建时无需再生成这两项。
- 本项目不需要安装依赖，暂时不必添加.gitignore。

点击Create repository。[GitHub官方创建说明](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)

## 3. 上传解压后的内容

进入仓库，选择Add file → Upload files；空仓库可点击uploading an existing file。

打开本机的ipo-financial-pr文件夹，把里面的全部文件和子文件夹拖入上传区。上传文件夹内的内容，使SKILL.md、README.md和LICENSE处于仓库根目录，不要再套一层同名目录。不要只上传ZIP。

提交说明可填写Initial release v1.0.0。自己的新仓库若允许直接提交默认分支，可选该方式；若选择新分支，按提示创建并合并Pull Request。[GitHub官方上传说明](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)

## 4. 检查

- 首页能正常显示README。
- 从SKILL.md能打开references中的文件。
- LICENSE显示MIT，当前署名为IPO Financial PR contributors；如需个人或机构署名，可在首次公开前调整为你有权使用的署名。
- 没有误上传额外的客户资料或原始参考附件。
- 项目文档将2026-09-11写作规则资料基线，不承诺所有条款均已核验或一直有效。

完成后，复制浏览器地址栏里的仓库链接即可分享。

## 5. 后续维护

小幅修改可在GitHub文件页面编辑后提交；多个文件更新时，上传对应修改并检查差异，删除已被替代的旧文件，防止留下多套互相冲突的版本。更新说明写入CHANGELOG。

本对话中的个人Skill与GitHub公开仓库不自动同步。后续更新时，明确哪一版是基准，再把同一份修改同步到另一个版本。

## 许可证

本包按MIT准备，允许商业使用、修改与分发，并要求保留版权及许可声明。见[许可证正文](../LICENSE)和[MIT说明](https://choosealicense.com/licenses/mit/)。公开资料链接不因此转由本项目授权。
