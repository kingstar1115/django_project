<p align="center">
  <a href="https://newpanjing.github.io/simpleui/">
    <img alt="Simpleui" src="https://github.com/newpanjing/simpleui/raw/2.0/images/simpleui-logo.png" width="140">
  </a>
</p>
<p align="center">让Django Admin简单而友好</p>
<p align="center">
Simple and friendly.
Django admin theme the simpleui
</p>
<p align="center">
  <a href="https://github.com/996icu/996.ICU/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-Anti%20996-blue.svg"></a>
  <a href="https://github.com/alibaba/ice"><img src="https://img.shields.io/badge/developing%20with-Simpleui-2077ff.svg"></a>
  <a href="https://pypi.org/project/django-simpleui/#history"><img src="https://img.shields.io/pypi/v/django-simpleui.svg"></a>
</p>

---

<a href="https://www.88cto.com/admin/">
  <img alt="demo" src="https://github.com/newpanjing/simpleui/raw/master/images/图片1.png" width="420" align="right" style="max-width: 50%">
</a>


simpleui
-----

✨ 官方与社区共同维护；持续更新，满足日常开发之所需。

⚡️ 多标签页面，各个模块更加清晰明了。配以最流行的后台设计风格，让Django Admin更加强大。

🎯 配置简单，极速上手，在settings.py中加入simpleui后启动立即生效，效率提升 100%！让后端开发得心应手。

☕️ Element，一套为开发者、设计师和产品经理准备的基于 Vue 2.0 的桌面端组件库。

🎨 Django Admin默认界面设计语言存在着的一些不足，比如色彩单一，大量线条的使用，分割化明显。将这些不足归类一下就是界面单调、雷同性明显、缺少惊喜。我们认为新的平台类视觉风格可以打破这些束缚，尝试一些新的探索，启发传统的设计认知,因此结合当下设计趋势，构思了Element+Django Admin的Simpleui。让Django Admin和Element产生完美的交互。

# 开始使用
详细步骤请浏览 [快速上手指南](./QUICK.md)。 也可以参考[Demo](#在线Demo)

+ 安装
```python
pip install django-simpleui
```
+ 升级
```python
pip install django-simpleui --upgrade
```
+ 克隆源码本地安装
```shell
git clone https://github.com/newpanjing/simpleui
cd simpleui
python setup.py sdist install
```
用pip或者源码方式安装simpleui后，在自己项目的settings.py文件中INSTALLED_APPS的第一行加入`simpleui`

## 常见问题:

1. 如果关闭debug模式后，请执行以下命令将simpleui静态文件静态文件克隆到根目录
    ```shell
    python3 manage.py collectstatic
    ```
2. 克隆静态文件出错
请在settings.py文件中加入：
    ```shell
    STATIC_ROOT = os.path.join(BASE_DIR, "static")
    ```
3. 其他问题请参考[django官方文档](https://docs.djangoproject.com/zh-hans/2.2/)。


# 在线Demo
> 权限受限，只能查看模块的相关数据，不能操作。如果要体验全部功能，请在自己的系统安装simpleui查看效果。

+ 地址：[https://www.88cto.com/admin/](https://www.88cto.com/admin/)
+ 用户名：demo
+ 密码：demo123456

## QQ群
+ QQ群号:786576510

## 赞助💰
如果你觉得simpleui对你有帮助，你可以赞助我们一杯开发，鼓励我们继续开发维护下去。
![扫码赞助](https://github.com/newpanjing/simpleui/raw/master/images/pay.png)
