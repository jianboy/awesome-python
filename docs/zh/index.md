# Awesome Python 

搜集整理一些开源python框架，类库，软件和资源。

---

## Web后台系统

*Libraries for administrative interfaces.*

* [ajenti](https://github.com/ajenti/ajenti) - 后台管理面板。
* [django-grappelli](https://grappelliproject.com/) - Django管理界面的爵士皮肤。
* [django-jet](https://github.com/geex-arts/django-jet) - Django管理界面的现代响应模板，具有改进的功能。
* [django-suit](https://djangosuit.com/) - 替代Django管理界面 (仅用于非商业用途免费)。
* [django-xadmin](https://github.com/sshwsfc/xadmin) - Django admin的直接替换带有很多好处。
* [flask-admin](https://github.com/flask-admin) - 简单且可扩展的Flask管理接口框架。
* [flower](https://github.com/mher/flower) - 芹菜的实时监控和网络管理。
* [jet-bridge](https://github.com/jet-admin/jet-bridge) - 管理面板框架，适用于具有良好UI的任何应用程序 (例如Jet Django)。
* [wooey](https://github.com/wooey/wooey) - 一个Django应用程序，它为Python脚本创建自动web ui。

## 算法和设计模式

*数据结构、算法和设计模式的Python实现。另请参阅 [令人敬畏的算法](https://github.com/tayllan/awesome-algorithms)。*

* 算法
	* [algorithms](https://github.com/keon/algorithms) - 数据结构和算法的最小示例。
	* [python-ds](https://github.com/prabhupant/python-ds) - 用于编码访谈的数据结构和算法的集合。
	* [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) - 排序集合的快速和纯Python实现。
	* [TheAlgorithms](https://github.com/TheAlgorithms/Python) - 用Python实现的所有算法。
* 设计模式
	* [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) - 一个简单而有效的库，用于实现常见的设计模式。
	* [python-patterns](https://github.com/faif/python-patterns) - Python中的设计模式集合。
	* [transitions](https://github.com/pytransitions/transitions) - 一种轻量级的，面向对象的有限状态机实现。

## ASGI服务器

*[ASGI](https://asgi.readthedocs.io/en/latest/) - 兼容的web服务器。*

* [daphne](https://github.com/django/daphne) - 用于ASGI和asgi-http的HTTP，HTTP2和WebSocket协议服务器。
* [uvicorn](https://github.com/encode/uvicorn) - 使用uvloop和httptools的闪电般的ASGI服务器实现。

## 异步编程

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python标准库) 异步I/O，事件循环，协程和任务。
-[awesome-asyncio](https://github.com/timofurrer/awesome-asyncio)
* [trio](https://github.com/python-trio/trio) - 异步并发和I/O的友好库。
* [Twisted](https://twistedmatrix.com/trac/) - 事件驱动的网络引擎。
* [uvloop](https://github.com/MagicStack/uvloop) - 超快速异步事件循环。

## 音频

*用于处理音频及其元数据的库。*

* 音频
	* [audioread](https://github.com/beetbox/audioread) - 跨库 (GStreamer Core Audio MAD FFmpeg) 音频解码。
	* [dejavu](https://github.com/worldveil/dejavu) - 音频指纹和识别。
	* [kapre](https://github.com/keunwoochoi/kapre) - Keras音频预处理器。
	* [librosa](https://github.com/librosa/librosa) - 用于音频和音乐分析的Python库。
	* [matchering](https://github.com/sergree/matchering) - 用于自动参考音频母带的库。
	* [mingus](http://bspaans.github.io/python-mingus/) - 具有MIDI文件和播放支持的高级音乐理论和符号包。
	* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - 音频特征提取，分类，分割和应用。
	* [pydub](https://github.com/jiaaro/pydub) - 操作音频与一个简单和容易的高级接口。
	* [TimeSide](https://github.com/Parisson/TimeSide) - 开放网络音频处理框架。
* 元数据
	* [beets](https://github.com/beetbox/beets) - 音乐库经理和 [MusicBrainz](https://musicbrainz.org/) 标签。
	* [eyeD3](https://github.com/nicfit/eyeD3) - 用于处理音频文件的工具，特别是包含ID3元数据的MP3文件。
	* [mutagen](https://github.com/quodlibet/mutagen) - 用于处理音频元数据的Python模块。
	* [tinytag](https://github.com/devsnd/tinytag) - 用于读取MP3，OGG，FLAC和Wave文件的音乐元数据的库。

## 身份验证

*用于实施身份验证方案的库。*

* OAuth
	* [authlib](https://github.com/lepture/authlib) - JavaScript对象签名和加密草案实现。
	* [django-allauth](https://github.com/pennersr/django-allauth) - Django的 “只是工作” 的身份验证应用程序。
	* [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - OAuth 2 Django好东西。
	* [oauthlib](https://github.com/idan/oauthlib) - OAuth请求签名逻辑的通用且彻底的实现。
	* [python-oauth2](https://github.com/joestump/python-oauth2) - 经过全面测试的抽象接口，用于创建OAuth客户端和服务器。
	* [python-social-auth](https://github.com/omab/python-social-auth) - 一种易于设置的社交身份验证机制。
* JWT
	* [pyjwt](https://github.com/jpadilla/pyjwt) - Python中的JSON Web令牌实现。
	* [python-jose](https://github.com/mpdavis/python-jose/) - Python中的JOSE实现。
	* [python-jwt](https://github.com/davedoesdev/python-jwt) - 用于生成和验证JSON Web令牌的模块。

## 构建工具

*从源代码编译软件。*

* [BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html) - 适用于嵌入式Linux的类似制作工具。
* [buildout](http://www.buildout.org/en/latest/) - 用于从多个部分创建，组装和部署应用程序的构建系统。
* [Platforio](https://github.com/platformio/platforio-core) - 一种控制台工具，用于使用不同的开发平台构建代码。
* [pybuilder](https://github.com/pybuilder/pybuilder) - 用纯Python编写的连续构建工具。
* [SCons](http://www.scons.org/) - 一种软件构建工具。

## 内置类增强

*用于增强Python内置类的库。*

* [attrs](https://github.com/python-attrs/attrs) - 替换类定义中的 “__ init __” 、 “__ eq __” 、 “__ repr __” 等样板。
* [bidict](https://github.com/jab/bidict) - 高效，Pythonic双向地图数据结构和相关功能 ..
* [Box](https://github.com/cdgriffith/Box) - 具有高级点符号访问权限的Python词典。
* [dataclasses](https://docs.python.org/3/library/dataclasses.html) - (Python标准库) 数据类。
* [DottedDict](https://github.com/carlosescri/DottedDict) - 一种库，提供了一种使用虚线路径符号访问列表和dict的方法。

## CMS

*内容管理系统。*

* [django-cms](https://www.django django-cms.org/en/) - 基于Django的开源企业CMS。
* [feincms](https://github.com/feincms/feincms) - 基于Django构建的最先进的内容管理系统之一。
* [indico](https://github.com/indico/indico) - 功能丰富的事件管理系统，由 @ [CERN](https://en.wikipedia.org/wiki/CERN) 制作。
* [Kotti](https://github.com/Kotti/Kotti) - 基于金字塔构建的高级Pythonic web应用程序框架。
* [mezzanine](https://github.com/stephenmcd/mezzanine) - 功能强大，一致且灵活的内容管理平台。
* [plone](https://plone.org/) - 建立在开源应用程序服务器Zope之上的CMS。
* [quokka](https://github.com/rochacbruno/quokka) - 灵活，可扩展，由烧瓶和MongoDB供电的小型CMS。
* [wagtail](https://wagtail.io/) - 一个Django内容管理系统。

## 缓存

*用于缓存数据的库。*

* [beaker](https://github.com/bbangert/beaker) - 用于会话和缓存的WSGI中间件。
* [django-cache-machine](https://github.com/django-cache-machine) - Django模型的自动缓存和失效。
* [django-cacheops](https://github.com/Suor/django-cacheops) - 具有自动粒度事件驱动失效的光滑ORM缓存。
* [dogpile.ca che](http:// dogpilecache.readthedocs.io/en/latest/) - dogpile.ca che是同一作者生产的烧杯的下一代替代品。
* [HermesCache](https://pypi.org/project/HermesCache/) - 具有基于标签的无效和dogpile效果预防的Python缓存库。
* [pylibmc](https://github.com/lericson/pylibmc) - 围绕 [libmemcached](https://libmemcached.org/libMemcached.html) 接口的Python包装器。
* [python-diskcache](http://www.grantjenks.com/docs/diskcache/) - SQLite和文件支持的缓存后端，查找速度比memcached和redis更快。

## 聊天工具

*用于聊天机器人开发的库。*

* [errbot](https://github.com/errbotio/errbot/) - 实现ChatOps的最简单，最受欢迎的聊天机器人。

## 代码分析

*静态分析、短绒和代码质量检查工具。另请参阅 [awesome-static-analysis](https://github.com/mre/awesome-static-analysis)。*

* 代码分析
	* [coala](https://github.com/coala/coala/) - 语言独立且易于扩展的代码分析应用程序。
	* [code2flow](https://github.com/scottrogowski/code2flow) - 把你的Python和JavaScript代码变成点流程图。
	* [探矿prospector者](https://github.com/PyCQA/prospector) - 分析Python代码的工具。
	* [pycallgraph](https://github.com/gak/pycallgraph) - 可视化您的Python应用程序的流程 (调用图) 的库。
	* [vulture](https://github.com/jendrikseipp/vulture) - 用于查找和分析死Python代码的工具。
* 代码检测
	* [flake8](https://pypi.org/project/flake8/) - 围绕 “pycodestyle” 、 “pyflakes” 和麦凯布的包装。
	* [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions)
	* [pylama](https://github.com/klen/pylama) - 用于Python和JavaScript的代码审计工具。
	* [pylint](https://www.pylint.org/) - 完全可定制的源代码分析器。
	* [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - 有史以来最严格，最有思想的python linter。
* 代码格式化器
	* [black](https://github.com/python/black) - 毫不妥协的Python代码格式化程序。
	* [isort](https://github.com/timothycrosley/isort) - 用于对导入进行排序的Python实用程序/库。
	* [yapf](https://github.com/google/yapf) - 谷歌的另一个Python代码格式化程序。
* 静态类型检查器，另请参阅 [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing)
	* [mypy](http:// mypy-lang.org/) - 在编译期间检查变量类型。
	* [pyre-check](https://github.com/facebook/pyre-check) - 性能类型检查。
	* [typeshed](https://github.com/python/typeshed) - Python的库存根集合，具有静态类型。
* 静态类型注释生成器
	* [MonkeyType](https://github.com/Instagram/MonkeyType) - Python系统，通过收集运行时类型生成静态类型注释。
	* [pytype](https://github.com/google/pytype) - Pytype检查和推断Python代码的类型-不需要类型注释。

## 命令行界面开发

*用于构建命令行应用程序的库。*

* 命令行应用程序开发
	* [cement](http://builtoncement.com/) - Python的CLI应用程序框架。
	* [click](http://click.pocoo.org/dev/) - 用于以可组合的方式创建漂亮的命令行界面的软件包。
	* [cliff](https://docs.openstack.org/developer/cliff/) - 用于创建具有多级命令的命令行程序的框架。
	* [docopt](http://docopt.org/) - Pythonic命令行参数解析器。
	* [python-fire](https://github.com/google/python-fire) - 用于从绝对任何Python对象创建命令行接口的库。
	* [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - 用于构建强大的交互式命令行的库。
* 终端渲染
	* [alive-progress](https://github.com/rsalmei/alive-progress) - 一种新的进度条，具有实时吞吐量，eta和非常酷的动画。
	* [asciimatics](https://github.com/peterbrittain/asciimatics) - 用于创建全屏文本UIs (从交互式表单到ASCII动画) 的软件包。
	* [bashplotlib](https://github.com/glamp/bashplotlib) - 在终端中制作基本地块。
	* [colorama](https://pypi.org/project/colorama/) - 跨平台彩色终端文本。
	* [rich](https://github.com/willmcgugan/rich) - Python库，用于在终端中富文本和漂亮的格式。还提供了一个很棒的 “richhandler” 日志处理程序。
	* [tqdm](https://github.com/tqdm/tqdm) - 快速，可扩展的进度条，用于循环和CLI。

## 命令行工具

*有用的基于CLI的工具，以提高生产力。*

* 生产力工具
	* [cookiecutter](https://github.com/audreyr/cookiecutter) - 从cookiecutters (项目模板) 创建项目的命令行实用程序。
	* [copier](https://github.com/pykong/copier) - 用于渲染项目模板的库和命令行实用程序。
	* [doitlive](https://github.com/sloria/doitlive) - 在终端中进行实时演示的工具。
	* [howdoi](https://github.com/gleitz/howdoi) - 通过命令行即时编码答案。
	* [Invoke](https://github.com/pyinvoke/invoke#readme) - 一种用于管理面向shell的子进程并将可执行Python代码组织到可执行命令的任务中的工具。
	* [PathPicker](https://github.com/facebook/PathPicker) - 从bash输出中选择文件。
	* [percol](https://github.com/mooz/percol) - 在UNIX上的传统管道概念中增加了交互式选择的味道。
	* [thefuck](https://github.com/nvbn/thefuck) - 更正您以前的控制台命令。
	* [tmuxp](https://github.com/tony/tmuxp) - [tmux](https://github.com/tmux/tmux) 会话管理器。
	* [try](https://github.com/timofurrer/try) - 尝试使用python软件包的简单CLI-从未如此简单。
* CLI增强功能
	* [httpie](https://github.com/jakubroztocil/httpie) - 命令行HTTP客户端，用户友好的cURL替换。
	* [iredis](https://github.com/laixintao/iredis) - 具有自动完成和语法高亮显示功能的Redis CLI。
	* [kube-shell](https://github.com/cloudnativelabs/kube-shell) - 用于使用Kubernetes CLI的集成外壳。
	* [litecli](https://github.com/dbcli/litecli) - 具有自动完成和语法高亮显示的SQLite CLI。
	* [mycli](https://github.com/dbcli/mycli) - 具有自动完成和语法突出显示功能的MySQL CLI。
	* [pgcli](https://github.com/dbcli/pgcli) - 具有自动完成和语法突出显示功能的PostgreSQL CLI。
	* [Saws](https://github.com/donnemartin/saws) - Superchared [aws-cli](https://github.com/aws/aws-cli)。

## 兼容性

*用于从Python 2迁移到3的库。*

* [modernize](https://github.com/PyCQA/modernize) - 为最终的Python 3迁移现代化Python代码。
* [python-future](http:// python-future.org/index.html) - Python 2和Python 3之间缺少的兼容性层。
* [six](https://pypi.org/project/six/) - Python 2和3兼容性实用程序。

## 计算机视觉

*计算机视觉库。*

* [EasyOCR](https://github.com/JaidedAI/EasyOCR) - 支持40种语言的即用型OCR。
* [Face Recognition](https://github.com/ageitgey/face_recognition) - 简单的人脸识别库。
* [Kornia](https://github.com/kornia/kornia/) - PyTorch的开源微分计算机视觉库。
* [OpenCV](https://opencv.org/) - 开源计算机视觉库。
* [pytesseract](https://github.com/madmaze/pytesseract) - [Google Tesseract OCR](https://github.com/tesseract-ocr) 的包装器。
* [SimpleCV](https://github.com/sightmachine/SimpleCV) - 用于构建计算机视觉应用程序的开源框架。
* [tesserocr](https://github.com/sirfz/tesserocr) - OCR的 “tesseract-ocr' API周围的另一个简单，枕头友好的包装器。

## 并发性和并行性

*用于并发和并行执行的库。另请参阅 [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio)。*

* [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - (Python标准库) 异步执行可调用的高级接口。
* [eventlet](http://eventlet.net/) - 支持WSGI的异步框架。
* [gevent](http://www.gevent.org/) - 基于协程的Python网络库，使用 [greenlet](https://github.com/python-greenlet/greenlet)。
* [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python标准库) 基于进程的并行性。
* [scoop](https://github.com/soravux/scoop) - Python中的可扩展并发操作。
* [uvloop](https://github.com/MagicStack/uvloop) - 在 “libuv” 之上的 “asyncio” 事件循环的超快速实现。

## 配置

*用于存储和解析配置选项的库。*

* [configobj](https://github.com/DiffSK/configobj) - 带有验证的ini文件解析器。
* [configparser](https://docs.python.org/3/library/configparser.html) - (Python标准库) ini文件解析器。
* [hydra](https://github.com/facebookresearch/hydra) - Hydra是一个优雅配置复杂应用程序的框架。
* [profig](https://profig.readthedocs.io/en/latest/) - 从具有值转换的多种格式进行配置。
* [python-deparple](https://github.com/henriquebastos/python-deparple) - 设置与代码的严格分离。

## 密码学

* [cryptography](https://cryptography.io/en/latest/) - 旨在向Python开发人员公开加密原语和配方的软件包。
* [paramiko](https://github.com/paramiko/paramiko) - 领先的本地Python SSHv2协议库。
* [passlib](https://passlib.readthedocs.io/en/stable/) - 安全的密码存储/散列库，非常高级。
* [pynacl](https://github.com/pyca/pynacl) - Python绑定到网络和密码学 (NaCl) 库。

## 数据分析

*用于数据分析的库。*

* [AWS Data Wrangler](https://github.com/awslabs/aws-Data-Wrangler) - AWS上的Pandas。
* [Blaze](https://github.com/blaze/blaze) - NumPy和熊猫大数据接口。
* [Open Mining](https://github.com/mining/mining) - 熊猫界面中的商业智能 (BI)。
* [Optimus](https://github.com/ironmussa/Optimus) - 使用PySpark轻松实现敏捷数据科学工作流程。
* [Orange](https://orane.biolab.si/) - 通过可视化编程或脚本进行数据挖掘，数据可视化，分析和机器学习。
* [Pandas](http://pandas.pydata.org/) - 提供高性能，易于使用的数据结构和数据分析工具的库。

## 数据验证

*用于验证数据的库。在许多情况下用于表格。*

* [Cerberus](https://github.com/pyeve/cerberus) - 轻量级和可扩展的数据验证库。
* [colander](https://docs.pylonsproject.org/projects/colander/en/latest/) - 验证和反序列化通过XML，JSON (HTML表单帖子) 获得的数据。
* [jsonschema](https://github.com/Julian/jsonschema) - Python的 [JSON Schema](http:// json-schema.org/) 的实现。
* [schema](https://github.com/keleshev/schema) - 用于验证Python数据结构的库。
* [Schematics](https://github.com/schematics/schematics) - 数据结构验证。
* [valideer](https://github.com/podio/valideer) - 轻量级可扩展数据验证和适应库。
* [voluptuous](https://github.com/alecthomas/voluptuous) - 一个Python数据验证库。

## 数据可视化

*用于可视化数据的库。另请参阅 [awesome-javascript](https://github.com/sorrycc/awesome-javascript # 数据可视化)。*

* [Altair](https://github.com/altair-viz/altair) - Python的声明性统计可视化库。
* [Bokeh](https://github.com/bokeh/bokeh) - Python的交互式网络绘图。
* [bqplot](https://github.com/bloomberg/bqplot) - Jupyter笔记本的交互式绘图库。
* [Cartopy](https://github.com/SciTools/cartopy) - 支持matplotlib的制图python库。
* [Dash](https://plot.ly/products/dash/) - 建立在烧瓶的顶部，React和Plotly针对分析web应用程序。
	* [awesome-dash](https://github.com/Acrotrend/awesome-dash)
* [diagrams](https://github.com/mingrammer/diagrams) - 图表作为代码。
* [Matplotlib](http://matplotlib.org/) - Python 2D绘图库。
* [plotnine](https://github.com/has2k1/plotnine) - 基于ggplot2的Python图形语法。
* [Pygal](http://www.pygal.org/en/latest/) - Python SVG图表创建者。
* [PyGraphviz](https://pypi.org/project/pygraphviz/) - 与 [Graphviz](http://www.graphviz.org/) 的Python接口。
* [PyQtGraph](http://www.pyqtgraph.org/) - 交互式和实时2D/3D/图像绘图和科学/工程小部件。
* [Seaborn](https://github.com/mwaskom/seaborn) - 使用Matplotlib进行统计数据可视化。
* [VisPy](https://github.com/vispy/vispy) - 基于OpenGL的高性能科学可视化。

## 数据库

*用Python实现的数据库。*

* [pickleDB](https://github.com/patx/pickledb) - 适用于Python的简单轻巧的键值存储。
* [tinydb](https://github.com/msiemens/tinydb) - 一个微小的，面向文档的数据库。
* [ZODB](https://github.com/zopefoundation/ZODB) - Python的本机对象数据库。一个键值和对象图数据库。

## 数据库驱动程序

*用于连接和操作数据库的库。*

* MySQL-[awesome-mysql](http:// shlomi-noach.github.io/awesome-mysql/)
	* [mysqlclient](https://github.com/PyMySQL/mysqlclient-python) - 支持Python 3的MySQL连接器 ([mysql-python](https://sourceforge.net/projects/mysql-python/) fork)。
	* [PyMySQL](https://github.com/PyMySQL/PyMySQL) - 与MySQL-Python兼容的纯python mysql驱动程序。
* PostgreSQL-[awesome-postgres](https://github.com/dhamaniasad/awesome-postgres)
	* [psycopg2](http://initd.org/psycopg/) - 适用于Python的最受欢迎的PostgreSQL适配器。
	* [queries](https://github.com/gmr/queries) - 用于与PostgreSQL交互的psycopg2库的包装器。
* SQlite-[-sqlite](https://github.com/planetopendata/awesome-sqlite)
	* [sqlite3](https://docs.python.org/3/library/sqlite3.html) - (Python标准库) 符合DB的SQlite接口-API 2.0
	* [SuperSQLite](https://github.com/plasticityai/supersqlite) - 建立在 [apsw](https://github.com/rogerbinns/apsw) 之上的增压SQLite库。
* 其他关系数据库
	* [clickhouse-driver](https://github.com/mymarilyn/clickhouse-driver) - 具有ClickHouse本机接口的Python驱动程序。
	* [pymssql](https://pymssql.readthedocs.io/en/latest/) - 到Microsoft SQL Server的简单数据库接口。
* NoSQL数据库
	* [cassandra-driver](https://github.com/datastax/python-driver) - Apache Cassandra的Python驱动程序。
	* [happybase](https://github.com/wbolster/happybase) - 适用于Apache HBase的开发人员友好的库。
	* [kafka-python](https://github.com/dpkp/kafka-python) - Apache Kafka的Python客户端。
	* [py2neo](https://py2neo.org/) - 用于使用Neo4j的客户端库和工具包。
	* [pymongo](https://github.com/mongodb/mongo-python-driver) - MongoDB的官方Python客户端。
	* [redis-py](https://github.com/andymccurdy/redis-py) - 用于Redis的Python客户端。
* 异步客户端
	* [motor](https://github.com/mongodb/motor) - 用于MongoDB的异步Python驱动程序。

## 日期和时间

*用于处理日期和时间的库。*

* [Arrow](https://arrow.readthedocs.io/en/latest/) - 一个Python库，它提供了一种明智且人性化的方法来创建，操纵，格式化和转换日期，时间和时间戳。
* [Chronyk](https://github.com/KoffeinFlummi/Chronyk) - 一个Python 3库，用于解析人工编写的时间和日期。
* [Datetil](https://github.com/dateutil/dateutil) - 对标准Python [datetime](https://docs.python.org/3/library/datetime.html) 模块的扩展。
* [delorean](https://github.com/myusuf3/delorean/) - 一个库，用于清除处理日期时间的不便真相。
* [maya](https://github.com/timofurrer/maya) - 人类的日期时间。
* [moment](https://github.com/zachwill/moment) - 用于处理日期/时间的Python库。灵感来自 [Moment.js](http://momentjs.com/)。
* [Pendulum](https://github.com/sdispater/pendulum) - Python日期时间变得容易。
* [PyTime](https://github.com/shinux/PyTime) - 易于使用的Python模块，旨在通过字符串操作日期/时间/日期时间。
* [pytz](https://launchpad.net/pytz) - 世界时区定义，现代和历史。将 [tz数据库](https://en.wikipedia.org/wiki/Tz_database) 带入Python。
* [when.py](https://github.com/dirn/When.py) - 提供用户友好的功能，以帮助执行常见的日期和时间操作。

## 调试工具

*用于调试代码的库。*

* 类似pdb的调试器
	* [ipdb](https://github.com/gotcha/ipdb) - IPython启用 [pdb](https://docs.python.org/3/library/pdb.html)。
	* [pdb ](https://github.com/antocuni/pdb) - pdb的另一种直接替换。
	* [pudb](https://github.com/inducer/pudb) - 全屏，基于控制台的Python调试器。
	* [wdb](https://github.com/Kozea/wdb) - 通过WebSockets进行的不可能的web调试器。
* 追踪
	* [lptrace](https://github.com/khamidou/lptrace) - [strace](http:// man7.org/linux/man-pages/man1/strace.1.html) 用于Python程序。
	* [manhole](https://github.com/ionelmc/python-manhole) - 调试UNIX套接字连接，并为所有线程提供堆栈跟踪和交互式提示。
	* [pyringe](https://github.com/google/pyringe) - 调试器能够附加到Python进程并将代码注入到Python进程中。
	* [python-hunter](https://github.com/ionelmc/python-hunter) - 一个灵活的代码跟踪工具包。
* 分析器
	* [line_profiler](https://github.com/rkern/line_profiler) - 逐行分析。
	* [memory_profiler](https://github.com/fabianp/memory_profiler) - 监控Python代码的内存使用情况。
	* [py-spy](https://github.com/benfred/py-spy) - Python程序的采样分析器。用铁锈写的。
	* [pyflame](https://github.com/uber/pyflame) - Python的ptracing分析器。
	* [vprof](https://github.com/nvdv/vprof) - 可视化Python探查器。
* 其他
	* [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) - 显示Django的各种调试信息。
	* [django-devserver](https://github.com/dcramer/django-devserver) - Django的运行服务器的直接替换。
	* [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) - django-调试工具栏到烧瓶的端口。
	* [icecream](https://github.com/gruns/icecream) - 使用单个简单的函数调用检查变量，表达式和程序执行。
	* [pyelftools](https://github.com/eliben/pyelftools) - 解析和分析ELF文件和矮化调试信息。

## 深度学习

*神经网络和深度学习的框架。另请参阅 [awesome深度学习](https://github.com/ChristosChristofidis/awesome深度学习)。*

* [caffe](https://github.com/BVLC/caffe) - 深度学习的快速开放框架 ..
* [keras](https://github.com/keras-team/keras) - 高级神经网络库，能够在TensorFlow或Theano之上运行。
* [mxnet](https://github.com/dmlc/mxnet) - 旨在提高效率和灵活性的深度学习框架。
* [pytorch](https://github.com/pytorch/pytorch) - Python中的张量和动态神经网络，具有强大的GPU加速。
* [SerpentAI](https://github.com/SerpentAI/SerpentAI) - 游戏代理框架。使用任何电子游戏作为深度学习沙盒。
* [tensorflow](https://github.com/tensorflow/tensorflow) - 由Google创建的最受欢迎的深度学习框架。
* [Theano](https://github.com/Theano/Theano) - 快速数值计算库。

## DevOps工具

*用于DevOps的软件和库。*

* 配置管理
	* [ansible](https://github.com/ansible/ansible) - 一个完全简单的IT自动化平台。
	* [cloudinit](https://cloudinit.readthedocs.io/en/latest/) - 一个多分发包，用于处理云实例的早期初始化。
	* [OpenStack](https://www.openstack.org/) - 用于构建私有和公共云的开源软件。
	* [pyinfra](https://github.com/Fizzadar/pyinfra) - 通用的CLI工具和python库，用于自动化基础架构。
	* [saltstack](https://github.com/saltstack/salt) - 基础设施自动化和管理系统。
* SSH风格的部署
	* [cuisine](https://github.com/sebastien/cuisine) - 类似厨师的面料功能。
	* [fabric](https://github.com/fabric/fabric) - 用于远程执行和部署的简单Pythonic工具。
	* [fabtools](https://github.com/fabtools/fabtools) - 编写awesome结构文件的工具。
* 流程管理
	* [honcho](https://github.com/nickstenning/honcho) - [Foreman](https://github.com/ddollar/foreman) 的Python克隆，用于管理基于Procfile的应用程序。
	* [supervisor](https://github.com/Supervisor/supervisor) - UNIX的Supervisor过程控制系统。
* 监控
	* [psutil](https://github.com/giampaolo/psutil) - 跨平台进程和系统实用程序模块。
* 备份
	* [BorgBackup](https://www.borgbackup.org/) - 具有压缩和加密功能的重复数据删除归档器。
* 其他
	* [docker-compose](https://docs.docker.com/compose/) - 使用 [Docker](https://www.docker.com/) 的快速，隔离的开发环境。

## 分布式计算

*用于分布式计算的框架和库。*

* 批处理
	* [Task](https://github.com/dask/dask) - 用于分析计算的灵活并行计算库。
	* [luigi](https://github.com/spotify/luigi) - 一个模块，可帮助您构建复杂的批处理作业管道。
	* [mrjob](https://github.com/Yelp/mrjob) - 在Hadoop或Amazon Web服务上运行MapReduce作业。
	* [PySpark](https://pypi.org/project/pyspark/) - [Apache Spark](https://spark.apache.org/) Python API。
	* [Ray](https://github.com/ray-project/ray/) - 用于并行和分布式Python的系统，该系统统一了机器学习生态系统。
* 流处理
	* [faust](https://github.com/robinhood/faust) - 一个流处理库，将思想从 [Kafka Streams](https://kafka.apache.org/documentation/streams/) 移植到Python。
	* [streamparse](https://github.com/Parsely/streamparse) - 通过 [Apache Storm](http://storm.apache.org/) 针对实时数据流运行Python代码。

## 分布

*为发布分发创建打包的可执行文件的库。*

* [dh-virtualenv](https://github.com/spotify/dh-virtualenv) - 构建和分发virtualenv作为Debian软件包。
* [Nuitka](http://nuitka.net/) - 将脚本，模块，软件包编译为可执行文件或扩展模块。
* [py2app](http://pythonhosted.org/py2app/) - 冻结Python脚本 (Mac OS X)。
* [py2exe](http://www.py2exe.org/) - 冻结Python脚本 (Windows)。
* [pyarmor](https://github.com/dashingsoft/pyarmor) - 用于混淆python脚本，将混淆脚本绑定到固定计算机或使混淆脚本过期的工具。
* [PyInstaller](https://github.com/pyinstaller/pyinstaller) - 将Python程序转换为独立的可执行文件 (跨平台)。
* [pynsist](http://pynsist.readthedocs.io/en/latest/) - 用于构建Windows安装程序的工具，安装程序捆绑了Python本身。
* [shiv](https://github.com/linkedin/shiv) - 用于构建完全独立的zipapps (PEP 441) 的命令行实用程序，但包括所有依赖项。

## 文档

*用于生成项目文档的库。*

* [sphinx](https://github.com/sphinx-doc/sphinx/) - Python文档生成器。
	* [awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc)
* [pdoc](https://github.com/mitmproxy/pdoc) - Epydoc替换自动生成Python库的API文档。
* [pycco](https://github.com/pycco-docs/pycco) - 识字编程风格的文档生成器。

## 下载器

*用于下载的库。*

* [akshare](https://github.com/jindaxiang/akshare) - 为人类构建的财务数据接口库!
* [s3cmd](https://github.com/s3tools/s3cmd) - 用于管理Amazon S3和CloudFront的命令行工具。
* [s4cmd](https://github.com/bloomreach/s4cmd) - 超级S3命令行工具，具有更高的性能。
* [you-get](https://you-get.org/) - 用Python 3编写的YouTube/Youku/Niconico视频下载器。
* [youtube-dl](https://rg3.github.io/youtube-dl/) - 一个小型命令行程序，用于从YouTube下载视频。

## 电子商务

*用于电子商务和支付的框架和库。*

* [alipay](https://github.com/lxneng/alipay) - Python的非官方支付宝API。
* [Cartridge](https://github.com/stephenmcd/cartridge) - 使用夹层构建的购物车应用程序。
* [django-oscar](http://oscarcommerce.com/) - Django的开源电子商务框架。
* [django-shop](https://github.com/awesto/django-shop) - 基于Django的商店系统。
* [forex-python](https://github.com/MicroPyramid/forex-python) - 外汇汇率，比特币价格指数和货币转换。
* [merchant](https://github.com/agiliq/merchant) - 一个Django应用程序，用于接受各种付款处理器的付款。
* [money](https://github.com/carlospalol/money) - 具有可选的CLDR支持的语言环境感知格式和可扩展货币交换的 'Money' 类。
* [python-货币](https://github.com/Alir3z4/python-货币) - 显示货币格式及其肮脏的货币。
* [saleor](https://saleor.io/) - 无头开源电子商务平台。
* [shoop](https://www.shuup.com/en/) - 基于Django的开源电子商务平台。

## 编辑器插件和ide

* Emacs
	* [elpy](https://github.com/jorgenschaefer/elpy) - Emacs Python开发环境。
* Sublime Text
	* [anaconda](https://github.com/DamnWidget/anaconda) - Anaconda在功能齐全的Python开发IDE中转换您的崇高文本3。
	* [SublimeJEDI](https://github.com/srusskih/SublimeJEDI) - 令人敬畏的自动完成库绝地的崇高文本插件。
* Vim
	* [jedi-vim](https://github.com/davidhalter/jedi-vim) - Python绝地自动完成库的Vim绑定。
	* [python模式](https://github.com/python模式) - 一个将Vim变成Python IDE的多合一插件。
	* [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - 包括基于 [Jedi](https://github.com/davidhalter/jedi) 的Python完成引擎。
* Visual Studio
	* [PTVS](https://github.com/Microsoft/PTVS) - Visual Studio的Python工具。
* Visual Studio Code
	* [Python](https://marketplace.visualstudio.com/items？itemName= ms-python.python) - 官方VSCode扩展，对Python有丰富的支持。
* IDE
* [PyCharm](https://www.jetbrains.com/pycharm/) - JetBrains的商业Python IDE。有免费的社区版可用。
* [spyder](https://github.com/spyder-ide/spyder) - 开源Python IDE。

## 电子邮件

*用于发送和解析电子邮件的库。*

* 邮件服务器
	* [modoboa](https://github.com/modoboa/modoboa) - 包含现代Web UI的邮件托管和管理平台。
	* [salmon](https://github.com/moggers87/salmon) - Python邮件服务器。
	* 客户
	* [imbox](https://github.com/martinrusev/imbox) - Python IMAP为人类。
	* [yagmail](https://github.com/kootenpv/yagmail) - 另一个Gmail/SMTP客户端。
	* 其他
	* [flanker](https://github.com/mailgun/flanker) - 电子邮件地址和Mime解析库。
	* [mailer](https://github.com/marrow/mailer) - 高性能可扩展邮件传递框架。

## 企业应用程序集成

*企业环境中系统集成的平台和工具 *

* [Zato](https://zato.io) - Python中的ESB，SOA，REST，api和云集成。

## 环境管理

*用于Python版本和虚拟环境管理的库。*

* [pyenv](https://github.com/pyenv/pyenv) - 简单的Python版本管理。
* [virtualenv](https://github.com/pypa/virtualenv) - 创建隔离Python环境的工具。

## 文件

*用于文件操作和MIME类型检测的库。*

* [mimetypes](https://docs.python.org/3/library/mimetypes.html) - (Python标准库) 将文件名映射到MIME类型。
* [path.py](https://github.com/jaraco/path.py) - [os.path](https://docs.python.org/3/library/os.path.html) 的模块包装器。
* [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python标准库) 一个跨平台的，面向对象的路径库。
* [PyFilesystem2](https://github.com/pyfilesystem/pyfilesystem2) - Python的文件系统抽象层。
* [python-magic](https://github.com/ahupp/python-magic) - libmagic文件类型识别库的Python接口。
* [Unipath](https://github.com/mikeorr/Unipath) - 文件/目录操作的面向对象方法。
* [watchdog](https://github.com/gorakhargosh/watchdog) - 用于监视文件系统事件的API和shell实用程序。

## 外功能接口

*用于提供外函数接口的库。*

* [cffi](https://pypi.org/project/cffi/) - Python调用C代码的外部函数接口。
* [ctypes](https://docs.python.org/3/library/ctypes.html) - (Python标准库) 外函数接口，用于Python调用C代码。
* [PyCUDA](https://mathema.tician.de/software/pycuda/) - Nvidia CUDA API的Python包装器。
* [SWIG](http://www.swig.org/Doc1.3/Python.html) - 简化的包装器和接口生成器。

## 表单

*用于处理表单的库。*

* [Deform](https://github.com/Pylons/deform) - 受formish表单生成库影响的Python HTML表单生成库。
* [django-bootstrap3](https://github.com/dyve/django-bootstrap3) - Bootstrap 3与Django集成。
* [django-bootstrap4](https://github.com/zostera/django-bootstrap4) - 引导4与Django集成。
* [django-crispy-forms](https://github.com/django-crispy-forms) - 一个Django应用程序，可让您以非常优雅和干燥的方式创建漂亮的表格。
* [django-remote-forms](https://github.com/WiserTogether/django-remote-forms) - 一个独立于平台的Django表单序列化器。
* [WTForms](https://github.com/wtforms/wtforms) - 灵活的表单验证和渲染库。

## 函数式编程

*用Python进行函数式编程。*

* [Coconut](https://github.com/evhub/coconut) - Python的一种变体，用于简单，优雅，Pythonic函数编程。
* [CyToolz](https://github.com/pytoolz/cytoolz/) - “toolz” 的Cython实现: 高性能功能实用程序。
* [fn.py](https://github.com/kachayev/fn.py) - Python中的函数式编程: 实现缺少的功能以享受FP。
* [funcy](https://github.com/Suor/funcy) - 一种奇特而实用的功能工具。
* [more-itertools](https://github.com/erikrose/更多-itertools) - 除了 “itertools” 之外，更多用于对iterables进行操作的例程。
* [returns](https://github.com/dry-python/returns) - 一组类型安全的单子，变压器和合成实用程序。
* [Toolz](https://github.com/pytoolz/toolz) - 用于迭代器，函数和字典的功能实用程序的集合。

## 图形用户界面开发

*用于使用图形用户界面应用程序的库。*

* [curses](https://docs.python.org/3/library/curses.html) - 用于 [ncurses](http://www.gnu.org/software/ncurses/) 的内置包装器，用于创建终端GUI应用程序。
* [DearPyGui](https://github.com/RaylockLLC/DearPyGui/) - 一个简单的GPU加速Python GUI框架
* [Eel](https://github.com/ChrisKnott/Eel) - 一个用于制作简单的电子样离线HTML/JS GUI应用程序的库。
* [enaml](https://github.com/nucleic/enaml) - 使用QML等声明性语法创建漂亮的用户界面。
* [Flexx](https://github.com/zoofIO/flexx) - Flexx是用于创建GUI的纯Python工具包，该工具包使用web技术进行渲染。
* [Gooey](https://github.com/chriskiehl/Gooey) - 将命令行程序转换为具有一行的完整GUI应用程序。
* [kivy](https://kivy.org/) - 用于创建在Windows，Linux，Mac OS X，Android和iOS上运行的NUI应用程序的库。
* [pyglet](https://github.com/pyglet/pyglet) - 用于Python的跨平台窗口和多媒体库。
* [PyGObject](https://wiki.gnome.org/Projects/PyGObject) - 适用于GLib/GObject/GIO/GTK (GTK 3) 的Python绑定。
* [PyQt](https://doc.qt.io/qtforpython/) - [qt](https://www.qt.io/) 跨平台应用程序和UI框架的Python绑定。
* [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) - tkinter、Qt、WxPython和Remi的包装器。
* [pywebview](https://github.com/r0x0r/pywebview/) - 围绕webview组件的轻量级跨平台本机包装器。
* [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter是Python的事实上的标准GUI包。
* [Toga](https://github.com/pybee/toga) - Python原生，操作系统原生GUI工具包。
* [urwid](http://urwid.org/) - 用于创建终端GUI应用程序的库，并强烈支持小部件，事件，丰富的色彩等。
* [wxPython](https://wxpython.org/) - wxWidgets C类库与Python的混合。

## GraphQL

*用于使用GraphQL的库。*

* [graphene](https://github.com/graphql-python/graphene/) - Python的GraphQL框架。
* [Tartiflette-aiohttp](https://github.com/tartiflette/tartiflette-aiohttp/) - 基于 'aiohttp' 的包装器，用于Tartiflette通过HTTP公开GraphQL api。
* [Tartiflette-asgi](https://github.com/tartiflette/tartiflette-asgi/) - Tartiflette GraphQL引擎的ASGI支持。
* [Tartiflette](https://tartiflette. (io) - SDL-适用于Python 3.6和asyncio的第一个GraphQL引擎实现。

## 游戏开发。

*令人敬畏的游戏开发库。*

* [街机](https://api.Arcade.academy/en/latest/) - 街机是一个现代的Python框架，用于制作具有引人注目的图形和声音的游戏。
* [Cocos2d](http://cocos2d.org/) - cocos2d是用于构建2D游戏，演示和其他图形/交互式应用程序的框架。
* [Harfang3D](http://www.harfang3d.com) - 用于3D，VR和游戏开发的Python框架。
* [Panda3D](https://www.panda3d.org/) - 迪士尼开发的3D游戏引擎。
* [Pygame](http://www.pygame.org/news.html) - Pygame是一组专为编写游戏而设计的Python模块。
* [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre) - 用于Ogre 3D渲染引擎的Python绑定，可用于游戏，模拟和任何3D。
* [PyOpenGL](http://pyopengl.sourceforge.net/) - OpenGL及其相关api的Python ctyptypes绑定。
* [PySDL2](https://pysdl2.readthedocs.io) - SDL2库的基于ctypes的包装器。
* [RenPy](https://www.renpy.org/) - 视觉小说引擎。

## 地理位置

*用于地理编码地址和使用纬度和经度的库。*

* [django-countries](https://github.com/SmileyChris/django-国家) - 一个Django应用程序，为模型和表单提供国家/地区字段。
* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - 世界一流的地理网络框架。
* [GeoIP](https://github.com/maxmind/geoip-api-python) - MaxMind GeoIP遗留数据库的Python API。
* [geojson](https://github.com/frewsxcv/python-geojson) - GeoJSON的Python绑定和实用程序。
* [geopy](https://github.com/geopy/geopy) - Python地理编码工具箱。

## HTML操作

*用于使用HTML和XML的库。*

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - 提供用于迭代，搜索和修改HTML或XML的Pythonic习语。
* [bleach](https://github.com/mozilla/bleach) - 基于白名单的HTML清理和文本链接库。
* [cssutils](https://pypi.org/project/cssutils/) - Python的CSS库。
* [html5lib](https://github.com/html5lib/html5lib-python) - 一个符合标准的库，用于解析和序列化HTML文档和片段。
* [lxml](http://lxml.de/) - 一个非常快速，易于使用且通用的库，用于处理HTML和XML。
* [MarkupSafe](https://github.com/pallets/markupsafe) - 为Python实现XML/HTML/XHTML标记安全字符串。
* [pyquery](https://github.com/gawel/pyquery) - 一个类似jQuery的库，用于解析HTML。
* [untangle](https://github.com/stchris/untangle) - 将XML文档转换为Python对象，以便于访问。
* [WeasyPrint](http://weasyprint.org) - 用于HTML和CSS的可视渲染引擎，可以导出为PDF。
* [xmldataset](https://xmldatasetas.readthedocs.io/en/latest/) - 简单的XML解析。
* [xmltodict](https://github.com/martinblech/xmltodict) - 使用XML感觉就像在使用JSON一样。

## HTTP客户端

*用于使用HTTP的库。*

* [grequests](https://github.com/spyoungtech/grequests) - 请求gevent异步HTTP请求。
* [httplib2](https://github.com/httplib2) - 全面的HTTP客户端库。
* [httpx](https://github.com/encode/httpx) - Python的下一代HTTP客户端。
* [requests](https://github.com/psf/requests) - 人类的HTTP请求。
* [treq](https://github.com/twisted/treq) - Python请求，如建立在Twisted的HTTP客户端之上的API。
* [urllib3](https://github.com/shazow/urllib3) - 具有线程安全连接池，文件发布支持，健全友好的HTTP库。

## 硬件

*用于用硬件编程的库。*

* [ino](http://inotool.org/) - 用于使用 [Arduino](https://www.arduino.ccc/) 的命令行工具包。
* [keyboard](https://github.com/boppreh/keyboard) - 在Windows和Linux上挂钩并模拟全局键盘事件。
* [mouse](https://github.com/boppreh/mouse) - 在Windows和Linux上挂钩并模拟全局鼠标事件。
* [Pingo](http://www.pingo.io/) - pingo提供了统一的API来编程Raspberry Pi，pcDuino，Intel Galileo等设备。
* [PyUserInput](https://github.com/SavinaRoja/PyUserInput) - 用于跨平台控制鼠标和键盘的模块。
* [scapy](https://github.com/secdev/scapy) - 一个辉煌的数据包操作库。

## 图像处理

*用于处理图像的库。*

* [hmap](https://github.com/rossgoodwin/hmap) - 图像直方图重新映射。
* [imgSeek](https://sourceforge.net/projects/imgseek/) - 使用视觉相似性搜索图像集合的项目。
* [nude.py](https://github.com/hhatto/nude.py) - 裸体检测。
* [pagan](https://github.com/daboth/pagan) - 基于输入字符串和哈希的复古身份 (化身) 生成。
* [pillow](https://github.com/pyhton-pillow/Pillow) - Pillow是友好的 [PIL](http://www.pythonware.com/products/pil/) 叉。
* [pygram](https://github.com/ajkumar25/pygram) - 类似Instagram的图像过滤器。
* [PyMatting](http://github.com/pymatting/pymatting) - alpha matting的库。
* [python-barcode](https://github.com/WhyNotHugo/python-barcode) - 在没有额外依赖的Python中创建条形码。
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) - 纯Python QR码生成器。
* [pyvips](https://github.com/libvips/pyvips) - 具有低内存需求的快速图像处理库。
* [pywal](https://github.com/dylanaraps/pywal) - 从图像生成配色方案的工具。
* [Quads](https://github.com/fogleman/Quads) - 基于四叉树的计算机艺术。
* [scikit-image](http:// scikit-image.org/) - 用于 (科学) 图像处理的Python库。
* [thumbor](https://github.com/thumbor/thumbor) - 智能成像服务。它可以按需裁剪，调整大小和翻转图像。
* [wand](https://github.com/dahlia/wand) - [魔杖] 的Python绑定 (http://www.imagemagick.org/script/magick-wand.php)，ImageMagick的C API。

## 实现

*Python的实现。*

* [CLPython](https://github.com/metawilm/cl-python) - 用Common Lisp编写的Python编程语言的实现。
* [CPython](https://github.com/python/cpython) - **默认，最广泛使用的用C编写的Python编程语言的实现。**
* [Cython](http://cython.org/) - 优化Python的静态编译器。
* [grumpy](https://github.com/google/grumpy) - 比解释器更强大的cdpython2.7替换 (alpha) 的编译器。
* [IronPython](https://github.com/IronLanguages/ironpython3) - 用C # 编写的Python编程语言的实现。
* [Jython](https://hg.python.org/jython) - 用Java为JVM编写的Python编程语言的实现。
* [MicroPython](https://github.com/micropython/micropython) - 一种精益高效的Python编程语言实现。
* [Numba](http://numba.pydata.org/) - 针对科学Python的Python JIT编译器到LLVM。
* [PeachPy](https://github.com/Maratyszcza/PeachPy) - 嵌入Python的x86-64汇编程序。
* [Pyjion](https://github.com/Microsoft/Pyjion) - 基于CoreCLR的Python JIT。
* [PyPy](https://foss.heptapod.net/pypy/pypy) - Python语言的非常快速且兼容的实现。
* [Pyston](https://github.com/dropbox/pyston) - 使用JIT技术的Python实现。
* [Stackless Python](https://github.com/无堆栈-dev/无堆栈) - Python编程语言的增强版本。

## 交互式解释器

*交互式Python解释器 (REPL)。*

* [bpython](https://github.com/bpython/bpython) - Python解释器的精美界面。
* [Jupyter Notebook (IPython)](https://jupyter.org) - 丰富的工具包，可帮助您充分利用交互式使用Python。
* [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)
* [ptpython](https://github.com/jonathanslenders/ptpython) - 建立在 [Python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) 之上的高级python REPL。

## 国际化

*用于使用i18n的库。*

* [Babel](http://babel.pocoo.org/en/latest/) - Python的国际化库。
* [PyICU](https://github.com/ovalhub/pyicu) - Unicode C库 ([ICU](http://site.icu-project.org/)) 的国际组件包装器。

## 作业计划程序

*用于调度作业的库。*

* [Airflow](https://airflow.apache.org/) - 气流是一个以编程方式创作，安排和监视工作流的平台。
* [APScheduler](http:// apscheduler.readthedocs.io/en/latest/) - 一种轻巧但功能强大的进程内任务计划程序，可让您安排功能。
* [django-schedule](https://github.com/thauber/django-schedule) - Django的日历应用程序。
* [doit](http://pydoit.org/) - 任务运行器和构建工具。
* [gunnery](https://github.com/gunnery/gunnery) - 用于具有基于web的界面的分布式系统的多功能任务执行工具。
* [Joblib](https://joblib.readthedocs.io/) - 一组工具，用于在Python中提供轻量级流水线。
* [Plan](https://github.com/fengsp/plan) - 像魅力一样在Python中编写crontab文件。
* [Prefect](https://github.com/PrefectHQ/prefect) - 现代的工作流编排框架，可轻松构建，调度和监视强大的数据管道。
* [schedule](https://github.com/dbader/schedule) - 适用于人类的Python作业调度。
* [Spiff](https://github.com/knipknap/SpiffWorkflow) - 在纯Python中实现的强大工作流引擎。
* [TaskFlow](https://docs.openstack.org/developer/taskflow/) - 一个Python库，有助于使任务执行变得简单，一致和可靠。

## 日志记录

*用于生成和处理日志的库。*

* [logbook](http://logbook.readthedocs.io/en/stable/) - Python的日志记录替换。
* [logging](https://docs.python.org/3/library/logging.html) - (Python标准库) Python的日志记录工具。
* [loguru](https://github.com/Delgan/loguru) - 旨在带来愉快的Python日志库。
* [sentry-python](https://github.com/getsentry/sentry-python) - 适用于Python的Sentry SDK。
* [structlog](https://www.structlog.org/en/stable/) - 结构化日志记录变得容易。

## 机器学习

*用于机器学习的库。另请参阅 [awesome机器学习](https://github.com/josephmisiti/awesome机器学习 # python)。*

* [gym](https://github.com/openai/gym) - 用于开发和比较强化学习算法的工具包。
* [H2O](https://github.com/h2oai/h2o-3) - 开源快速可扩展机器学习平台。
* [Metrics](https://github.com/benhamner/Metrics) - 机器学习评估指标。
* [MindsDB](https://github.com/mindsdb/mindsdb) - MindsDB是用于现有数据库的开源AI层，可让您轻松地使用标准查询开发，训练和部署最先进的机器学习模型。
* [NuPIC](https://github.com/numenta/nupic) - 数字智能计算平台。
* [scikit-learn](http:// scikit-learn.org/) - 用于机器学习的最流行的Python库。
* [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/) 的可扩展机器学习库。
* [vowpal_porpoise](https://github.com/josephreisinger/元音 _ 海豚) - [元音Wabbit](https://github.com/JohnLangford/元音 _ 海豚/) 的轻量级Python包装器。
* [xgboost](https://github.com/dmlc/xgboost) - 可扩展，可移植和分布式梯度提升库。

## Microsoft Windows

*Microsoft Windows的Python编程。*

* [Python(x，y)](http:// python-xy.github.io/) - 基于Qt和Spyder的面向科学应用程序的Python发行版。
* [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/) - Python扩展包的非官方Windows二进制文件。
* [PythonNet](https://github.com/pythonnet/pythonnet) - 与的Python集成。NET公共语言运行时 (CLR)。
* [PyWin32](https://github.com/mhammond/pywin32) - Windows的Python扩展。
* [WinPython](https://winpython.github.io/) - 适用于Windows 7/8的可移植开发环境。

## 杂项

*不适合上述类别的有用库或工具。*

* [blinker](https://github.com/jek/blinker) - 快速的Python进程中的信号/事件调度系统。
* [boltons](https://github.com/mahmoud/boltons) - 一组纯Python实用程序。
* [itsdangerous](https://github.com/pallets/itsdangerous) - 将受信任的数据传递到不受信任的环境的各种帮助。
* [magenta](https://github.com/magenta/magenta) - 一种使用人工智能生成音乐和艺术的工具。
* [pluginbase](https://github.com/mitsuhiko/pluginbase) - 一个简单但灵活的Python插件系统。
* [tryton](http://www.tryton.org/) - 通用业务框架。

## 自然语言处理

*用于使用人类语言的库。*

-一般
	* [gensim](https://github.com/稀有技术/gensim) - 人类主题建模。
	* [langid.py](https://github.com/saffsd/langid.py) - 独立语言识别系统。
	* [nltk](http://www.nltk.org/) - 用于构建Python程序以处理人类语言数据的领先平台。
	* [pattern](https://github.com/clips/pattern) - 一个web挖掘模块。
	* [polyglot](https://github.com/aboSamoor/polyglot) - 支持数百种语言的自然语言管道。
	* [pytext](https://github.com/facebookresearch/pytext) - 基于PyTorch的自然语言建模框架。
	* [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) - 一种可用于研究的快速深度学习NLP原型的工具包。
	* [spacy](https://spacy.io/) - 用于Python和Cython中的工业强度自然语言处理的库。
	* [Stanza](https://github.com/stanfordnlp/stanza) - 斯坦福NLP集团的官方Python库，支持60种语言。
-中文
	* [funNLP](https://github.com/fighting41love/funNLP) - 中文NLP的工具和数据集集合。
	* [jieba](https://github.com/fxsjy/jieba) - 最受欢迎的中文文本分割库。
	* [pkuseg-python](https://github.com/lancopku/pkuseg-python) - 用于各个领域的中文分词的工具包。
	* [snownlp](https://github.com/isnowfy/snownlp) - 用于处理中文文本的库。

## 网络虚拟化

*用于虚拟网络和SDN (软件定义网络) 的工具和库。*

* [mininet](https://github.com/mininet/mininet) - 用Python编写的流行网络模拟器和API。
* [napalm](https://github.com/napalm-automation/napalm) - 跨供应商API来操纵网络设备。
* [pox](https://github.com/noxrepo/pox) - 基于Python的SDN控制应用程序，例如OpenFlow SDN控制器。

## 新闻提要

*用于构建用户活动的库。*

* [django-activity-stream](https://github.com/justquick/django-activity-stream) - 从您网站上的操作生成通用活动流。
* [Stream Framework](https://github.com/tschellenbach/Stream-Framework) - 使用Cassandra和Redis构建新闻提要和通知系统。

## ORM

*实现对象关系映射或数据映射技术的库。*

* 关系数据库
	* [Django模型](https://docs.djangoproject.com/en/dev/topics/db/models/) - Django ORM。
	* [SQLAlchemy](https://www.sqlalchemy.org/) - Python SQL工具包和对象关系映射器。
	* [awesome-方术](https://github.com/dahlia/awesome-方术)
	* [数据集](https://github.com/pudo/dataset) - 在数据库中存储Python字典-与SQLite，MySQL和PostgreSQL一起使用。
	* [演说家](https://github.com/sdispater/orator) - 演说家ORM提供了一个简单而漂亮的ActiveRecord实现。
	* [orm](https://github.com/encode/orm) - 异步ORM。
	* [peewee](https://github.com/coleifer/peewee) - 一个小的，富有表现力的ORM。
	* [pony](https://github.com/ponyorm/pony/) - ORM，为SQL提供面向生成器的接口。
	* [pydal](https://github.com/web2py/pydal/) - 纯Python数据库抽象层。
* NoSQL数据库
	* [hot-redis](https://github.com/stephenmcd/hot-redis) - Redis的丰富Python数据类型。
	* [mongoengine](https://github.com/MongoEngine/mongoengine) - 用于使用MongoDB的Python对象-文档-映射器。
	* [PynamoDB](https://github.com/pynamodb/PynamoDB) - [Amazon DynamoDB](https://aws.amazon.com/dynamodb/) 的Pythonic接口。
	* [redisco](https://github.com/kiddouk/redisco) - 用于在Redis中保存的简单模型和容器的Python库。

## 包管理

*用于包和依赖管理的库。*

* [pip](https://pip.pypa.io/en/stable/) - Python的软件包安装程序。
	* [pip-tools](https://github.com/jazzband/pip-tools) - 一组工具，可使固定的Python依赖项保持新鲜。
	* [皮皮](https://pypi.org/)
* [conda](https://github.com/conda/conda/) - 跨平台，与Python无关的二进制包管理器。
	* [诗歌](https://github.com/sdispater/poetry) - Python依赖管理和包装变得容易。

## 软件包存储库

*本地PyPI存储库服务器和代理。*

* [bandersnatch](https://github.com/pypa/bandersnatch/) - Python打包权威 (PyPA) 提供的PyPI镜像工具。
* [devpi](https://github.com/devpi/devpi) - PyPI服务器和打包/测试/发布工具。
* [localshop](https://github.com/jazzband/localshop) - 本地PyPI服务器 (自定义软件包和pypi的自动镜像)。
* [warehouse](https://github.com/pypa/warehouse) - 下一代Python软件包存储库 (PyPI)。

## 渗透测试

*用于渗透测试的框架和工具。*

* [fsociety](https://github.com/Manisso/fsociety) - 渗透测试框架。
* [setoolkit](https://github.com/trustedsec/social-engineer-toolkit) - 社会工程工具包。
* [sqlmap](https://github.com/sqlmapproject/sqlmap) - 自动SQL注入和数据库接管工具。

## 权限

*允许或拒绝用户访问数据或功能的库。*

* [django-guardian](https://github.com/django-guardian) - 实现Django 1.2的每个对象权限
* [django-rules](https://github.com/dfunckt/django-rules) - 一个微小但功能强大的应用程序，为Django提供对象级权限，而无需数据库。

## 进程

*用于启动和与操作系统进程通信的库。*

* [delegator.py](https://github.com/amitt001/delegator.py) - [子进程](https://docs.python.org/3/library/subprocess.html) 用于人类2.0。
* [sarge](https://sarge.readthedocs.io/en/latest/) - 另一个子进程包装器。
* [sh](https://github.com/amoffat/sh) - Python的完整子进程替代品。

## 推荐系统

*用于构建推荐系统的库。*

* [annoy](https://github.com/spotify/annoy) - 针对内存使用进行了优化的C /Python中的近似最近邻居。
* [fastFM](https://github.com/ibayer/fastFM) - 用于分解机器的库。
* [隐式](https://github.com/benfred/implicit) - 用于隐式数据集的协作过滤的快速Python实现。
* [libffm](https://github.com/guestwalk/libffm) - 用于场感知分解机 (FFM) 的库。
* [lightfm](https://github.com/lyst/lightfm) - 许多流行推荐算法的Python实现。
* [spotlight](https://github.com/maciejkula/spotlight) - 使用PyTorch的深度推荐模型。
* [Surprise](https://github.com/NicolasHug/Surprise) - 用于构建和分析推荐系统的scikit。
* [tensorrec](https://github.com/jfkirk/tensorrec) - TensorFlow中的推荐引擎框架。

## 重构

*Python重构工具和库 *

 * [自行车修理人](http://bicyclerepair.sourceforge.net/) - 自行车修理人，Python的重构工具。
 * [Bowler](https://pybowler.io/) - 现代Python的安全代码重构。
 * [Rope](https://github.com/python-rope/rope) - Rope是一个python重构库。

## RESTful API

*用于构建RESTful api的库。*

* Django
	* [django-rest-framework](http:// www.django-rest-framework.org/) - 一个强大而灵活的工具包，用于构建web api。
	* [django-tastypie](http://tastypieapi.org/) - 为Django应用程序创建美味的api。
* Flask
	* [eve](https://github.com/pyeve/eve) - 由Flask，MongoDB和良好意图提供支持的REST API框架。
	* [烧瓶-api](https://github.com/烧瓶-api) - 烧瓶的可浏览Web api。
	* [烧瓶-restful](https://github.com/烧瓶-restful) - 快速构建烧瓶的REST api。
* Pyramid
* [cornice](https://github.com/Cornices/cornice) - 金字塔的RESTful框架。
* 框架不可知
	* [apistar](https://github.com/encode/apistar) - 为Python 3设计的智能Web API框架。
	* [falcon](https://github.com/falconry/falcon) - 用于构建云api和web应用程序后端的高性能框架。
	* [fastapi](https://github.com/tiangolo/fastapi) - 一个现代，快速的web框架，用于基于标准Python类型提示使用Python 3.6构建api。
	* [hug](https://github.com/hugapi/hug) - 一个Python 3框架，用于干净地公开api。
	* [sandman2](https://github.com/jeffknupp/sandman2) - 现有数据库驱动系统的自动REST api。
	* [sanic](https://github.com/巨大成功/sanic) - 编写快速运行的Python 3.6 web服务器和web框架。
	* [vibora](https://vibora.io/) - 受Flask启发的快速，高效和异步Web框架。

## 机器人技术

*机器人库。*

* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) - 这是各种具有可视化功能的机器人算法的汇编。
* [rospy](http://wiki.ros.org/rospy) - 这是ROS (机器人操作系统) 的库。

## RPC服务器

*RPC兼容服务器。*

* [RPyC](https://github.com/tomerfiliba/rpyc) (远程Python调用) - 用于Python的透明对称RPC库
* [zeroRPC](https://github.com/0rpc/zerorpc-python) - zerorpc是基于 [ZeroMQ](http://zeromq.org/) 和 [MessagePack](http://msgpack.org/) 的灵活RPC实现。

## 科学

*科学计算库。另请参阅 [Python-for-Scientists](https://github.com/TomNicholas/Python-for-Scientists)。*

* [astropy](http://www.astropy.org/) - 天文学的社区Python库。
* [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) - 为全自动高通量测序分析提供最佳实践管道。
* [bccb](https://github.com/chapmanb/bcbb) - 与生物学分析相关的有用代码的收集。
* [生物修道](http://biopython.org/wiki/Main_Page) - 生物修道是一组免费的生物计算工具。
* [cclib](http://cclib.github.io/) - 用于解析和解释计算化学软件包结果的库。
* [color](http:// colour-science.org/) - 实现了大量的色彩理论转换和算法。
* [空手道俱乐部](https://github.com/benedekrozemberczki/karateclub) - 图形结构化数据的无监督机器学习工具箱。
* [NetworkX](https://networkx.github.io/) - 用于复杂网络的高生产率软件。
* [NIPY](http://nipy.org) - 神经成像工具包的集合。
* [NumPy](http://www.numpy.org/) - 使用Python进行科学计算的基本软件包。
* [ObsPy](https://github.com/obspy/obspy/wiki/) - 地震学的Python工具箱。
* [Open Babel](http://openbabel.org/wiki/Main_Page) - 一种化学工具箱，旨在讲多种化学数据语言。
* [PyDy](http://www.pydy.org/) - Python Dynamics的缩写，用于协助工作流进行动态运动建模。
* [PyMC](https://github.com/pymc-devs/pymc3) - 马尔可夫链蒙特卡罗抽样工具包。
* [QuTiP](http://qutip.org/) - Python中的量子工具箱。
* [RDKit](http://www.rdkit.org/) - 化学信息学和机器学习软件。
* [SciPy](https://www.scipy.org/) - 基于Python的数学，科学和工程开源软件生态系统。
* [SimPy](https://gitlab.com/team-simpy/simpy) - 基于过程的离散事件仿真框架。
* [statsmodels](https://github.com/statsmodels/statsmodels) - Python中的统计建模和计量经济学。
* [SymPy](https://github.com/sympy/sympy) - 符号数学的Python库。
* [Zipline](https://github.com/quantopian/zipline) - 一个Pythonic算法交易库。

## 搜索

*用于对数据进行索引和执行搜索查询的库和软件。*

* [django-haystack](https://github.com/django-haystack) - Django的模块化搜索。
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - 用于Elasticsearch的官方高级Python客户端。
* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) - [Elasticsearch] 的官方低级Python客户端 (https://www.elasticsearch)。
* [pysolr](https://github.com/django-haystack/pysolr) - [Apache Solr](https://lucene.apache.org/solr/) 的轻量级Python包装器。
* [whoosh](http:// whoosh.readthedocs.io/en/latest/) - 快速，纯Python搜索引擎库。

## 序列化

*用于序列化复杂数据类型的库 *

* [棉花糖](https://github.com/棉花糖代码/棉花糖) - 一个轻量级库，用于将复杂对象转换为简单的Python数据类型。
* [Pysimdjson](https://github.com/TkTech/pysimdjson) - [simdjson](https://github.com/lemire/simdjson) 的Python绑定。
* [Python-rapidjson](https://github.com/python-rapidjson) - 围绕 [RapidJSON](https://github.com/Tencent/rapidjson) 的Python包装器。
* [Ultrajson](https://github.com/esnme/ultrajson) - 用Python绑定用C编写的快速JSON解码器和编码器。

## 无服务器框架

*用于开发无服务器Python代码的框架。*

* [Python-lambda](https://github.com/nficano/python-lambda) - 用于在AWS Lambda中开发和部署Python代码的工具包。
* [Zappa](https://github.com/Miserlou/Zappa) - 用于在AWS Lambda和API网关上部署WSGI应用程序的工具。

## 外壳

*基于Python的外壳。*

* [Xonsh](https://github.com/xonsh/xonsh/) - 一种Python驱动的跨平台Unix凝视shell语言和命令提示符。

## 特定格式处理

*用于解析和处理特定文本格式的库。*

* 一般
	* [tablib](https://github.com/jazzband/tablib) - 用于XLS，CSV，JSON，YAML中的表格数据集的模块。
* 办公室
	* [docxtpl](https://github.com/elapouya/python-docx-模板) - 通过jinja2模板编辑docx文档
	* [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - 用于读取和写入Excel 2010 xlsx/xlsm/xltx/xltm文件的库。
	* [pyexcel](https://github.com/pyexcel/pyexcel) - 提供一个用于读取，处理和写入csv，ods，xls，xlsx和xlsm文件的API。
	* [python-docx](https://github.com/python-openxml/python-docx) - 读取、查询和修改Microsoft Word 2007/2008 docx文件。
	* [python-pptx](https://github.com/scanny/python-pptx) - 用于创建和更新PowerPoint (.pptx) 文件的Python库。
	* [unoconv](https://github.com/unoconv/unoconv) - 在LibreOffice/OpenOffice支持的任何文档格式之间进行转换。
	* [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - 用于创建Excel的Python模块。xlsx文件。
	* [xlwings](https://github.com/ZoomerAnalytics/xlwings) - BSD许可的库，可轻松从Excel调用Python，反之亦然。
	* [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - 从Excel文件中写入和读取数据以及格式化信息。
* PDF
	* [PDFMiner](https://github.com/euske/pdfminer) - 从PDF文档中提取信息的工具。
	* [Pydf2](https://github.com/mstamy2/pydf2) - 能够拆分，合并和转换PDF页面的库。
	* [ReportLab](https://www.reportlab.com/opensource/) - 允许快速创建丰富的PDF文档。
* Markdown
	* [Mistune](https://github.com/lepture/mistune) - 最快和全功能的Markdown纯Python解析器。
	* [Python-Markdown](https://github.com/waylan/Python-Markdown) - John Gruber Markdown的Python实现。
* YAML
* [PyYAML](http://pyyaml.org/) - Python的YAML实现。
* CSV
	* [csvkit](https://github.com/wireservice/csvkit) - 用于转换为CSV并使用CSV的实用程序。
* 存档
	* [unp](https://github.com/mitsuhiko/unp) - 一种命令行工具，可以轻松解压缩档案。

## 静态站点生成器

*静态站点生成器是一种软件，该软件将一些文本模板作为输入，并在输出上生成HTML文件。*

* [lektor](https://github.com/lektor/lektor) - 易于使用的静态CMS和博客引擎。
* [makesite](https://github.com/sunainapai/makesite) - 简单，轻巧，无魔术的静态站点/博客生成器 (< 130行)。
* [mkdocs](https://github.com/mkdocs/mkdocs/) - Markdown友好文档生成器。
* [nikola](https://github.com/getnikola/nikola) - 静态网站和博客生成器。
* [pelican](https://github.com/getpelican/pelican) - 支持Markdown和reST语法的静态站点生成器。

## 标记

*用于标记项目的库。*

* [django-taggit](https://github.com/jazzband/django-taggit) - Django的简单标记。

## 任务队列

*用于处理任务队列的库。*

* [celery](https://docs.celeryproject.org/en/stable/) - 基于分布式消息传递的异步任务队列/作业队列。
* [dramatiq](https://github.com/Bogdanp/dramatiq) - 适用于Python 3的快速可靠的后台任务处理库。
* [huey](https://github.com/coleifer/huey) - 小多线程任务队列。
* [mrq](https://github.com/pricingassistant/mrq) - 使用Redis & gevent在Python中的分布式工作任务队列。
* [rq](https://github.com/rq/rq) - Python的简单作业队列。

## 模板引擎

*用于模板化和模板化的库和工具。*

* [Genshi](https://genshi.edgewall.org/) - Python模板工具包，用于生成web感知输出。
* [Jinja2](https://github.com/pallets/jinja) - 现代和设计师友好的模板语言。
* [Mako](http://www.makotemplates.org/) - Python平台的超快和轻量级模板。

## 测试

*用于测试代码库和生成测试数据的库。*

* 测试框架
	* [假设](https://github.com/HypothesisWorks/hypothesis) - 假设是一个高级的Quickcheck风格的基于属性的测试库。
	* [nose2](https://github.com/nose-devs/nose2) - 基于 “unittest2” 的 “鼻子” 的后继者。
	* [pytest](https://docs.pytest.org/en/latest/) - 成熟的全功能Python测试工具。
	* [机器人框架](https://github.com/robotframework/robotframework) - 通用测试自动化框架。
	* [unittest](https://docs.python.org/3/library/unittest.html) - (Python标准库) 单元测试框架。
* 测试跑步者
	* [绿色](https://github.com/CleanCut/green) - 干净，多彩的测试跑步者。
	* [mamba](http://nestorsalceda.github.io/mamba/) - Python的权威测试工具。出生在BDD旗下。
	* [tox](https://tox.readthedocs.io/en/latest/) - 自动构建和测试多个Python版本中的发行版
* 图形用户界面/网络测试
	* [locust](https://github.com/locustio/locust) - 用Python编写的可扩展用户负载测试工具。
	* [PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI是用于人类的跨平台GUI自动化Python模块。
	* [Schemathesis](https://github.com/kiwicom/schemathesis) - 一种用于对使用开放API/Swagger规范构建的web应用程序进行基于属性的自动测试的工具。
	* [Selenium](https://pypi.org/project/selenium/) - [Selenium](http://www.seleniumhq.org/) WebDriver的Python绑定。
	* [sixpack](https://github.com/seatgeek/sixpack) - 与语言无关的A/B测试框架。
	* [splinter](https://github.com/cobrateam/splinter) - 用于测试web应用程序的开源工具。
* 模拟
	* [doublex](https://pypi.org/project/doublex/) - 强大的Python测试双打框架。
	* [freezegun](https://github.com/spulec/freezegun) - 通过嘲笑datetime模块穿越时间。
	* [httmock](https://github.com/patrys/httmock) - 一个模拟的Python 2.6和3.2请求库。
	* [httpretty](https://github.com/gabrielfalcao/HTTPretty) - Python的HTTP请求模拟工具。
	* [模拟](https://docs.python.org/3/library/unittest.mock.html) - (Python标准库) 一个嘲笑和修补库。
	* [mocket](https://github.com/mindflayer/python-mocket) - 具有gevent/asyncio/SSL支持的套接字模拟框架。
	* [响应](https://github.com/getsentry/responses) - 用于模拟请求Python库的实用程序库。
	* [VCR.py](https://github.com/kevin1024/vcrpy) - 在测试中记录和重放HTTP交互。
* 对象工厂
	* [factory_boy](https://github.com/FactoryBoy/factory_boy) - Python的测试夹具替代品。
	* [混合器](https://github.com/klen/mixer) - 另一个固定装置的更换。支持Django、Flask、SQLAlchemy、Peewee等。
	* [模型 _ 妈妈](https://github.com/vandersonmota/模型 _ 妈妈) - 创建随机夹具在Django中测试。
* 代码覆盖范围
	* [覆盖率](https://pypi.org/project/coverage/) - 代码覆盖率测量。
* 伪造数据
	* [fake2db](https://github.com/emirozer/fake2db) - 假数据库生成器。
	* [faker](https://github.com/joke2k/faker) - 生成伪造数据的Python包。
	* [mimesis](https://github.com/lk-geimfari/mimesis) - 是一个Python库，可帮助您生成伪造数据。
	* [雷达](https://pypi.org/project/radar/) - 生成随机日期时间/时间。

## 文本处理

*用于解析和处理纯文本的库。*

* 一般
	* [chardet](https://github.com/chardet/chardet) - Python 2/3兼容字符编码检测器。
	* [difflib](https://docs.python.org/3/library/difflib.html) - (Python标准库) 计算增量的助手。
	* [ftfy](https://github.com/LuminosoInsight/python-ftfy) - 使Unicode文本更少的破坏和更一致的自动。
	* [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - 模糊字符串匹配。
	* [Levenshtein](https://github.com/ztane/python-Levenshtein/) - 快速计算Levenshtein距离和字符串相似性。
	* [盘古.py](https://github.com/vinta/pangu.py) - 偏执文字间距。
	* [pyfiglet](https://github.com/pwaller/pyfiglet) - 用Python编写的figlet的实现。
	* [pypinyin](https://github.com/mozillazg/python-拼音) - 将中文汉字 (漢字) 转换为拼音 (拼音)。
	* [textdistance](https://github.com/orsinium/textdistance) - 用30个算法计算序列之间的距离。
	* [unidecode](https://pypi.org/project/Unidecode/) - Unicode文本的ASCII音译。
* Slugify
	* [awesome-slugify](https://github.com/dimka665/awesome-slugify) - 一个可以保留unicode的Python slugify库。
	* [python-slugify](https://github.com/un33k/python-slugify) - 将unicode转换为ASCII的Python slugify库。
	* [unicode-slugify](https://github.com/mozilla/unicode-slugify) - 一个slugifier，以Django作为依赖项生成unicode slug。
* 唯一标识符
	* [hashids](https://github.com/davidaurelio/hashids-python) - Python中 [hashids](http://hashids.org) 的实现。
	* [shortuuid](https://github.com/skorokithakis/shortuuid) - 一个简洁，明确和URL安全的uuid的生成器库。
* 解析器
	* [ply](https://github.com/dabeaz/ply) - Python的lex和yacc解析工具的实现。
	* [pygments](http://pygments.org/) - 通用语法荧光笔。
	* [pyparsing](https://github.com/pyparsing/pyparsing) - 用于生成解析器的通用框架。
	* [python-nameparser](https://github.com/derek73/python-nameparser) - 将人名解析到它们的各个组件中。
	* [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - 解析，格式化，存储和验证国际电话号码。
	* [python用户代理](https://github.com/selwin/python用户代理) - 浏览器用户代理解析器。
	* [sqlparse](https://github.com/andialbrecht/sqlparse) - 非验证SQL解析器。

## 第三方api

*用于访问第三方服务api的库。另请参阅 [Python API包装器和库列表](https://github.com/realpython/python api包装器列表)。*

* [apache-libcloud](https://libcloud.apache.org/) - 一个适用于所有云的Python库。
* [boto3](https://github.com/boto/boto3) - 亚马逊网络服务的Python接口。
* [django-wordpress](https://github.com/istrategylabs/django-wordpress) - Django的WordPress模型和视图。
* [facebook-sdk](https://github.com/mobolic/facebook-sdk) - Facebook平台Python SDK。
* [google-api-python-客户端](https://github.com/google/google-api-python-客户端) - 适用于Python的Google api客户端库。
* [gspread](https://github.com/burnash/gspread) - 谷歌电子表格Python API。
* [twython](https://github.com/ryanmcgrath/twython) - Twitter API的Python包装器。

## 网址操作

*用于解析url的库。*

* [furl](https://github.com/gruns/furl) - 一个小的Python库，使解析和操作url变得容易。
* [purl](https://github.com/codeinthehole/purl) - 一个简单，不可变的URL类，带有用于询问和操纵的干净API。
* [pyshorteners](https://github.com/ellisonleao/pyshorteners) - 一个纯Python URL缩短lib。
* [webargs](https://github.com/棉花糖代码/webargs) - 一个友好的库，用于解析HTTP请求参数，内置支持流行的web框架。

## 视频

*用于处理视频和gif的库。*

* [moviepy](https://zulko.github.io/moviepy/) - 用于基于脚本的电影编辑的模块，具有多种格式，包括动画gif。
* [scikit-视频](https://github.com/aizvorski/scikit-视频) - SciPy的视频处理例程。
* [vidgear](https://github.com/abhiTronix/vidgear) - 最强大的多线程视频处理框架。

## 网络资产管理

*用于管理、压缩和缩小网站资产的工具。*

* [django-compressor](https://github.com/django-compressor) - 将链接和内联JavaScript或CSS压缩到单个缓存文件中。
* [django-pipeline](https://github.com/jazzband/django-pipeline) - 用于Django的资产打包库。
* [django-storages](https://github.com/jschneier/django-storages) - Django的自定义存储后端的集合。
* [fanstatic](http://www.fanstatic.org/en/latest/) - 将静态文件依赖项打包、优化并作为Python包提供服务。
* [fileconveyor](http://wimleers.com/fileconveyor) - 用于检测文件并将其同步到cdn，S3和FTP的守护程序。
* [烧瓶-资产](https://github.com/miracle2k/烧瓶-资产) - 帮助您将webasset集成到您的烧瓶应用程序中。
* [webassets](https://github.com/miracle2k/webassets) - 捆绑，优化和管理静态资源的独特缓存破坏url。

## Web内容提取

*用于提取web内容的库。*

* [html2text](https://github.com/Alir3z4/html2text) - 将HTML转换为Markdown格式的文本。
* [lassie](https://github.com/michaelhelmick/lassie) - 人类的网络内容检索。
* [micawber](https://github.com/coleifer/micawber) - 一个小库，用于从url中提取丰富的内容。
* [报纸](https://github.com/codelucas/newspaper) - Python中的新闻提取、文章提取和内容整理。
* [python-可读性](https://github.com/buriy/python-可读性) - arc90的可读性工具的快速Python端口。
* [请求-html](https://github.com/psf/请求-html) - Pythonic HTML解析为人类。
* [Summy](https://github.com/miso-belica/summy) - 用于自动汇总文本文档和HTML页面的模块。
* [textract](https://github.com/deanmalmgren/textract) - 从任何文档，Word，PowerPoint，pdf等中提取文本。
* [toapi](https://github.com/gaojiuli/toapi) - 每个网站都提供api。

## 网络爬行

*库自动进行网页抓取。*

* [cola](https://github.com/chineking/cola) - 一个分布式爬行框架。
* [feedparser](https://pythonhosted.org/feedparser/) - 通用feed解析器。
* [抓取](https://github.com/lorien/grab) - 网站抓取框架。
* [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) - 用于自动与网站交互的Python库。
* [·波西亚](https://github.com/scrapinghub/portia) - 视觉刮擦。
* [pyspider](https://github.com/binux/pyspider) - 一个强大的蜘蛛系统。
* [robobrowser](https://github.com/jmcarp/robobrowser) - 一个简单的Pythonic库，无需独立的web浏览器即可浏览web。
* [scrapy](https://scrapy.org/) - 快速的高级屏幕抓取和web抓取框架。

## 网络框架

*传统的全栈web框架。另请参阅 [RESTful API](https://github.com/vinta/awesome-python # restful-api)。*

* 同步
	*[Django](https://www.djangoproject.com/) - Python中最流行的web框架。
	* [awesome-姜戈](https://github.com/shahraizali/awesome-姜戈)
	* [awesome-姜戈](https://github.com/wsvincent/awesome-姜戈)
	* [Flask](http://flask.pocoo.org/) - Python的微框架。
	* [令人敬畏的烧瓶](https://github.com/humiaogodu/令人敬畏的烧瓶)
	*[Pyramid](https://pylonsproject.org/) - 一个小型，快速，脚踏实地的开源Python web框架。
	*[Aye-金字塔](https://github.com/uralbash/令人敬畏-金字塔)
	* [Masonite](https://github. com/MasoniteFramework/masonite) - 以开发人员为中心的现代Python web框架。
* 异步
	* [Tornado](http://www.tornadoweb.org/en/latest/) - 一个web框架和异步网络库。

## 网络插座

*用于使用WebSocket的库。*

* [高速公路-python](https://github.com/crossbario/高速公路-python) - 扭曲和 [异步] 上的Python的WebSocket & WAMP (https://docs.python.org/3/library/asyncio.html)。
* [频道](https://github.com/django/channels) - 开发人员友好的Django异步。
* [websockets](https://github.com/aaugustin/websockets) - 用于构建WebSocket服务器和客户端的库，重点是正确性和简单性。

## WSGI服务器

*WSGI兼容的网络服务器。*

* [bjoern](https://github.com/jonashaag/bjoern) - 异步，非常快，用C编写。
* [gunicorn](https://github.com/benoitc/gunicorn) - 预分叉，从Ruby的独角兽项目移植。
* [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) - 一个项目旨在开发用于构建托管服务的完整堆栈，用C编写。
* [waitress](https://github.com/Pylons/waitress) - 多线程，权力金字塔。
* [werkzeug](https://github.com/pallets/werkzeug) - Python的WSGI实用程序库，它为Flask提供动力，可以轻松地嵌入到您自己的项目中。

