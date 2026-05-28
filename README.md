# hitsz-cv-chinese

## 说明
本仓库修改自威海学长简历，改为哈工深适合版本

## 致谢
本模板基于[西北工业大学中文CV模板](https://www.overleaf.com/latex/templates/npu-cv/mncqzxhvfzrx)和[北京邮电大学BUPT简历模板](https://github.com/Yokumii/BUPT-CV-Template)进行调整，感谢两个模板的作者！


## 使用说明

1. 克隆本仓库：
   ```bash
   git clone https://github.com/IceFerryLing/jian-li.git
   ```
   没有git的同学可以直接下载zip文件，解压后使用

2. 安装依赖：需要使用 XeLaTeX 编译，可以安装Tex Live和MikTeX，Mac用户也可以安装MacTeX

3. 修改模板：
   - 在 `main.tex` 中填写个人信息
   - 替换 `images\avatar.png` 为个人照片

4. 编译简历：
   ```powershell
   xelatex main.tex
   ```
   建议编译至少2遍，也可以在所在文件夹，运行PowerShell脚本`buildpdf.ps1`，可以直接实现编译，以及在确认后删除编译产生的临时文件

5. 查看结果：
   - 生成的 PDF 文件为 `main.pdf`
