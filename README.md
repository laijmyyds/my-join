# my-join

SCP 谜异档案中文维基的入站答题系统。

本项目是一个纯静态站点，部署于 GitHub Pages，通过 iframe 嵌入 Wikidot 的加入页面，为站点提供独立的入站答题与暗号验证功能。

---

## 项目结构

my-join/
- CNAME --> 自定义域名配置
- README.md --> 本文件
- index.html --> 答题入口页面
- verify.html --> 暗号验证页面


---

## 功能说明

### index.html

入站答题的主入口。申请人通过此页面完成入站测试，题目内容与站点世界观、站规、基本礼仪相关。

完成答题后，系统会生成一组唯一的入站暗号，申请人需将此暗号填入 Wikidot 的加入申请中。

### verify.html

暗号验证页面。用于校验申请人提交的暗号是否有效，并返回对应的抽题记录。

### CNAME

将 GitHub Pages 绑定到自定义子域名：
```text
https://scpmyjoin.laifan.dpdns.org
```

---

## 授权协议

本项目遵循 CC BY-SA 3.0 协议。

---

## 相关链接

- [SCP 谜异档案中文维基](https://scp-mysterious-wiki.wikidot.com/)
- [GitHub 仓库](https://github.com/laijmyyds/my-join)
