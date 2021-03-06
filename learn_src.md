
src 1:原文链接：http://en.cppreference.com/w/cpp/links/libs

src 2: https://zh.cppreference.com/w/cpp/links/libs

此页面的目的是构建开源 C++ 库的比较列表，使得人们在需要特定功能的实现时，不必浪费时间在网上（ DuckDuckGo 、谷歌、必应等）搜索。

若你知道可能对其他人有用的库，请在此添加到它的链接。能包含者无限制，除了必须能便捷地下载库源码。

以 “原态” 提供此页面 —— 希望这有用，但不提供任何担保。过时、误导或错误的链接可能出现于此。若你注意到这些错误，则改正它会很有意义。

包管理器
conan
vcpkg
build2
cget
hunter

通用

Boost - 大量通用库的汇集（ Boost 许可）
GSL -  Guideline Support Library 实现，为 Bjarne Stroustrup, Herb Sutter 和 Co 在《 C++ 核心方针》中推荐
BDE -  来自 Bloomberg L.P. 的 Bloomberg Development Environment 核心库（ Apache 许可）
Dlib - 网络、线程、图形用户界面、数据结构、线性代数、机器学习、 XML 及文本分析、数值优化、贝叶斯网络和大量其他任务（ Boost 许可）
JUCE - 扩展性的成熟跨平台 C++ 工具套（ GPL 许可）
Loki - 设计模式
Reason -  xml 、 xpath 、正则表达式、线程、接头、 http 、 sql 、日期时间、流、编码与解码、文件系统、压缩（ GPL 许可）
yomm2 - C++17 的开放式多方法（ Boost 许可）
Folly -  Facebook 开源库。设计带有构思中的实践性和效率设计的 C++11 组件库。
Abseil - Google 设计以补足 C++ 标准库的开源 C++ 库代码汇集。
cxxomfort - C++ 特性逆向移植（ C++11 到 C++03 及 C++1y 提案到 C++11/C++03 ）。
libsourcey - 高速网络化和多媒体编码的跨平台 C++11 库。 HTTP 、 WebSockets 、 TURN 、 STUN 、 Symple 及更多……
OnPosix - 在 POSIX 平台上提供各种抽象（例如线程、网络化、日志、 IPC 等）的 C++ 库。
Ultimate++ - 跨平台的迅速应用开发框架
CAF - C++ Actor Framework (CAF) 是开源的 C++11 行动者模型实现，特性为轻量而快速的行动者实现、消息的模式匹配、网络不可见消息传递及更多（ BSD 许可）。
cpp-mmf - 对 POSIX 或 Windows 封装映射到内存文件的 C++98 库
CommonPP - 多用途库，强调在项目中得出度规。 (BSD)
Better Enums - 反射性枚举（枚举到字符、迭代等），带 constexpr 支持。 (BSD)
Smart Enum - 给你的枚举 "to_string" 、 "from_string" 和更多。（ Boost 许可）
nytl - 通用的 C++17 唯头文件模板库。（ Boost 许可）
SaferCPlusPlus -  SaferCPlusPlus - 不安全的 C++ 原始工具的安全兼容替换品，包括指针、 int 和 std::vector 。（ Boost 许可）
fcppt -  Freundlich 的 C++ 工具套 (fcppt) 是聚焦于通过提供更好的类型和函数式编程改进 C++ 代码的库汇集。
bitfield.h - 位域结构设施，比基础语言设施更可移植 / 灵活。
composite_op.h - 基础类数据成员自省，繁琐且常常不可重入，但有时有用。
Abstract Intrusive Containers - 比 boost::intrusive 更灵活，但非 STL 兼容。
Yato - 现代 C++ (14/17) 的跨平台 STL 风格及 STL 兼容库，实现容器、范围、迭代器、类型特性和其他工具；行动者系统；类型安全配置接口（ Apache-2.0 ）
Kangaru - C++11 与 C++14 的依赖注入容器（ MIT 许可）
yaal - 算法、汇集、任意精度计算、泛型 DSL 文法驱动分析器及更多 (CC BY-ND-NC 4.0)
gsl-lite - C++98 、 C++11 及后续版本的 ISO C++ Guideline 支持库 (GSL) 的单文件唯头文件版本。
nonstd-lite - *-lite 仓库的亲属，将 C++11 后特性移植到古代 C++ 环境的迁移路径。
units - 编译时唯头文件的量纲分析及单位转换库，建立于 C++14 而无依赖。

交互
sockpp - 简单的现代 C++ 套接库
restbed - 设计以嵌入到宽范围的应用中的 C++ 为框架。
C++ REST SDK - 异步 HTTP 客户端及监听器、异步 Stream 、 URI 、 JSON
cpr - 现代 C++ HTTP 请求库
cpp-netlib - cpp-netlib ： C++ 网络库
tacopie - C++11 TCP 库
Boost.Asio - 异步及同步网络、定时器、序列 I/O
Boost.Beast - 建立于 Boost.Asio 顶上的 HTTP 及 WebSocket 库
gsoap - XML 数据绑定、快速 WSDL/SOAP/XML 网络服务、 WS 安全、 JSON/XML-RPC RESTful 服务的 C/C++ 开发工具套
POCO - 网络：加密、 HTTP ； ZIP 文件
omniORB - 最快速、完整而可移植的 CORBA ORB 在 C++ 中的实现
ACE - 异步网络、多路分离、报文发送
TAO -  CORBA
wvstreams
Unicomm - 异步网络、高层 TCP 交互框架
restful_mapper - 于 C++ 中消费 RESTful JSON API 的 ORM
zeromq - 快速消息队列
curlpp - CURL 库的 C++ 包装
Apache Thrift - Apache Thrift 软件框架，用于规模可变的跨语言服务开发，将软件栈与代码生成引擎结合，构建有效而无缝地在 C++ 、 Java 、 Python 、 PHP 、 Ruby 、 Erlang 、 Perl 、 Haskell 、 C# 、 Cocoa 、 JavaScript 、 Node.js 、 Smalltalk 、 Ocaml 、 Delphi 及其他语言间工作的服务。
libashttp - 异步 HTTP 客户端库
Simple C++ REST library - 在你的 C++ 应用中创建 REST API 的非常简单且自成文档的库
libtins - 网络包装制作及嗅探库
PcapPlusPlus - 多平台 C++ 网络嗅探和包装分析及制作框架
HTTPP - 简单、生产就绪的构建在 Boost 上的 HTTP 服务器，及构建在 libcurl 上的客户端。 (BSD)
The Silicon C++14 Web Framework - 快速而稳健的 Web APIs (MIT) 。
ngrest - 快速而简易的利用 JSON 的 RESTful 网络服务框架 (Apache2) 。
restc-cpp - 将痛苦从自 C++ 访问 JSON API 带走。 HTTP 客户端，原生 C++ 类到 / 自 JSON 的序列化，通过 boost::asio coroutines 携程的异步 IO 。 C++14 。 (MIT)
OpenDDS - DDS 实现
Breep - 基于事件、高层、点对点库，允许用户直接发送和接收对象。
uvw - 现代 C++ 书写的 libuv
rest_rpc - 现代、简单、易用的 rpc 框架
EasyHttp - 跨平台的 HTTP 客户端库，专注于可用性和速度，支持 http 响应缓存及更多（ MIT 许可）
nghttp2 -  HTTP/2 C 库及工具（服务器、客户端、代理和评测工具）（ MIT 许可）
IXWebSocket - 无依赖的开源 WebSocket + HTTP 库，支持 SSL 和逐条消息 deflate 的 WebSocket 扩展。
KCP -  快速可靠的 ARQ 协议，帮助应用减少网络延迟。（ MIT 许可）
seastar -  用 C++11 实现的高性能异步编程框架。
图形用户界面
Dear ImGui - 高度优化的不膨胀的图形用户界面库。
FLTK
nana[doc] - 用现代 C++ 风格的 GUI 编程（ Boost 许可）
nanogui[doc] -  最小化的跨平台器件库，适用于 OpenGL 3.x 或更高版本
WxWidgets[src][doc]
OWLNext - 对 OWL 的，用于在 Windows 上以标准 C++ 书写 GUI 应用的现代更新
tiny file dialogs - 单个 C C++ 跨平台文件（无初始化、无 main 循环、 6 种形态的函数调用）
CopperSpice
CopperSpice[src][doc] -  CopperSpice 是用于开发跨平台软件应用的 C++ 库集合。它在 LGPL V2.1 许可下发布。它使用现代理念的 C++ 并与 STL 无缝结合。 CopperSpice 派生自 Qt 框架。
CsSignal - 独立的 C++ 具线程信号 / 槽库
CsString - 独立的 C++ 具 Unicode 字符串库
libGuarded - 独立的 C++ 多线程库，用于管理对共享数据的访问
GTK+
glibmm
gtkmm
goocanvasmm
libglademm
libgnomecanvasmm
webkitgtk
flowcanvas
evince
Qt
Qt[src][doc]
qwtplot3d
qwt5 - 技术应用到 Qt Widgets
libdbusmenu-qt
QuickQanava - 直接在 Qt/QML 应用中画图的 C++14 库；项目主页： http://www.qanava.org
QuickProperties - QObject/QtObject 属性编辑的 C++/QML 库；项目主页： http://www.qanava.org

通用多媒体
SFML (Simple and Fast Multimedia Library)
SDL (Simple DirectMedia Layer) - 对音频、键盘、鼠标、操纵杆及图形硬件，经由平台上图形 API （通常为 OpenGL 或 Direct3D ）的跨平台低层访问（ zlib 许可）
SIGIL (Sound, Input, and Graphics Integration Library) - 文本、形状、输入、音频及 2D 图像的难以置信地简单的跨平台极简库
Cinder
openFrameworks
图形
cairomm
nux
pangomm
nanovg -  基于 openGL/DX/metal 的 2d 绘图库。
bgfx -  非常强大的跨平台图形渲染库，支持平台包括 Windows Mac Linux iOS Android Web，渲染后端包括 DX, opengl, metal webgl 等。

图像
gegl
stb.image
Adobe/boost GIL - 高层通用库，聚焦于 2D 图像上操作的算法。非常有限定 I/O 选项。
GraphicsMagick - 读、写、操纵 88 种主要格式的图像。于 2002 年分化自 ImageMagick
Skia Graphics Engine - Google 从 2005 年起的图形库，用于 Chrome 、 Chrome OS 、 Android 还有 Firefox 和 Sublime Text enwiki:Skia_Graphics_Engine
Anti-Grain Evolution - 跨平台 2D 光栅化及绘图引擎

打点
plotutils

格式
libraw
openexr
qimageblitz
imagemagick
djvulibre
poppler
SVG++
音频
soundtouch
KFR - 快速的现代 DSP 框架、 DFT/FFT 、 Audio 重采样、 FIR/IIR 滤波器、双二阶
Aquila - 跨平台 DSP 库
指纹识别
chromaprint
libofa
libmusicbrainz
格式
audiofile
flac
标签
id3lib
taglib
CD
libkcompactdisc
图像处理
opencv
dlib
ITK
OTB

视频
crystalhd
mjpegtools
libmatroska
libVLC
gstreamermm
3D 图形
Vulkan
OpenGL
bgfx - 跨平台、不知图形 API 、“带来你自己的引擎 / 框架” 风格的制图库。
Ogre3D
Diligent Engine - 现代跨平台低层 3D 图形库。
GLEW - OpenGL 功能加载
GLAD - 可定制的轻量库，用于加载 OpenGL 功能
Epoxy - GLEM 的现代后继者。在 GL 环境的一些种类间抽象，这使得有时比使用 GLEW 更加单。自 2015 起为 GTK+ 项目所用。
GLFW - OpenGL 窗口管理器
GLM - 制图用的唯头文件 C++ 数学库
hlsl++ - 使用 hlsl 语法的唯头文件 C++ 渲染库。支持 SSE 和 NEON
assimp - 3D 模型加载
VTK
Magnum - 游戏和数据可视化的轻量模块化的 C++11/C++14 图形中间件
Irrlicht
Horde3D
Visionaray - C++ 光束追踪模板库
Open CASCADE - 3D CAD/CAM/CAE 应用的 SDK
OpenSceneGraph
游戏引擎架构
EntityX
Anax
EntityPlus
EnTT
BOX2D - 物理引擎
国际化
IBM ICU
gettext
spirit-po - 快速的唯头文件库，分析 po 文件，并提供类似 GNU libintl 的接口。基于 boost::spirit 。

数学
stats++ - 先进、广泛的统计软件：数据收集及预处理、统计、机器学习及优化，拥有开放的 C++ 源码。
StatsLib - 统计分布函数的模板化唯头文件库。
alglib
ArrayFire High Performance Computation Library
GNU MP bignum C++ interface
BigNumber - 创建和计算任意长度整数的 C++ 类
Boost.Multiprecision
Boost.Math.Special Functions and Statistical Distributions
Boost.Random
NTL - A Library for doing Number Theory
cpp-measures - 处理物理度量的唯头文件 C++11 库
G+Smo - 等几何分析的跨平台库
C++ Matrix - 高性能且精确（例如极端情况）的矩阵数学库，带表达式模板算术运算符
Exact floating-point arithmetic library
RPNX Uniform Smooth Noise - N 维均匀分布的平滑噪声函数，以 C++ 实现。
数值计算
LibBF - 由 Bellard 开发的任意精度数值计算库，拥有一个将圆周率计算到数十亿位的示例程序
线性代数
Boost.uBLAS
Eigen
Armadillo
Blitz++
IT++
Dlib - linear algebra tools
Blaze
ETL
DecompLib - 唯头文件的 C++11 库，分解向量为正定加权基向量的集合。
优化
OptimLib - 非线性函数数值优化方法的 C++11 库。
图论
Boost.Graph
LEMON
OGDF - Open Graph Drawing Framework
NGraph - a simple (Network) Graph library in C++
GTpo - C++14 泛型图拓扑库，带 Protocol Buffer 序列化；项目主页： http://www.qanava.org
数的类库
cln
Universal -  通用数算术的 C++ 模板库，取代 IEEE 浮点（ MIT 许可）
计算几何
CGAL - 计算几何算法库
Wykobi - 计算几何库
PCL - 点云库
自动化理论
yasmine - C++11 UML state machine framework[src][doc]
物理与模拟
ReactPhysics3D - 进行 3D 模拟与游戏的 C++ 物理引擎
ProjectCHRONO - 开源多物理模拟引擎
Bullet - 游戏、视觉效果、机器人及加固学习的物理模拟
金融计算
QuantLib - Quantitative finance library
DataFrame -  C++ DataFrame —— 现代 C++ 中使用原生类型、连续内存存储，且无虚函数的 R 与 Pandas 数据框架。
并发
Intel TBB
OpenMP
Cpp-Taskflow - 带任务依赖的快速 C++ 并行编程
RaftLib - 类似并发行动者的 C++ 流
Thrust - CUDA 的仿 STL 算法及数据结构
ViennaCL - 带 OpenMP 、 CUDA 及 OpenCL 后端的线性代数及算法
VexCL - OpenCL 和 CUDA 的 C++ 表达式模板库
Boost.Compute - （非官方） OpenCL 的仿 STL 算法及数据结构
Boost.Interprocess
Boost.Thread
Boost.Atomic
Boost.Lockfree
Boost.MPI
Boost.Context
libopenmpi
libsimdpp
HPX - 任何规模的并行和分布式应用的通用 C++ 运行时系统
KOKKOS - C++ 中的编程模型，用于书写高性能的便携 HPC 应用
SObjectizer - 通过行动者和出版订阅模型，简化开发并发和事件驱动应用的 C++ 中的小型框架。
BlockingCollection - C++11 线程安全汇集类，模仿 .Net BlockingCollection 。
容器
Boost.Any
Boost.Array
Boost.Bimap
Boost.Container
Boost.Fusion
Boost.Heap
Boost.Pointer Container
Boost.Tuple
Boost.Variant
cpp-btree -  btree_map 、 btree_set 、 btree_multimap 、 btree_multiset 。
TdhLists
strict_variant - 快速而决不空的 variant ，目标 C++11 。阻止许多不想要的隐式转换。
eggs::variant - Eggs.Variant 是 C++11/14 的泛型、线程安全、有区别的联合体。值得注意的是它有很好的 constexpr 支持。
Ygg - 高性能容器和数据结构，例如红黑树、区间数和区间映射的侵入式 C++11 实现。
plf::list - std::list 实现，为缓存友好牺牲范围切割，导致更快的插入、擦除和迭代。
plf::stack - std::stack 容器适配器的随意访问替换容器，在栈环境中有优于 std::vector 和 std::deque 的性能。
plf::colony - 无序的 “类背包” 容器，在高度修改场景中性能优于 std:: 容器，同时维护指向未被擦除元素的合法指针，无关乎插入或擦除。
ring_span - Guy Davidson 与 Arthur O'Dwyer 的 ring_span —— 即环状缓冲区视图的简化实现。
Frozen -  constexpr 完美基于哈希的冻结集合与映射（ Apache 2.0 ）。
DataFrame -  C++ DataFrame —— 现代 C++ 中使用原生类型、连续内存存储，且无虚函数的 R 与 Pandas 数据框架。
元编程
Boost.MPL - 原初元编程库，目标为 C++03 ，慢
Boost.Hana - 类型与值的新元编程库
Boost.Mp11
Boost.CallableTraits
Metal - 使用饿元函数， 100% SFINAE 友好
Brigand - 使用饿元函数，为最佳性能优化
Meta - 使用饿元函数，在 metal 和 brigand 之间，相对于性能妥协
Boost.Metaparse - 编译时分析器库，从编译时字符串产生类型、值和元函数
Boost.Proto - 构建基于表达式模板的 EDSLs 的库
CoMeta - 轻量、唯头文件的 C++14 元编程库
visit_struct - 小规模反射库，提供 C++11 的结构体观察器。自容纳， 100-200 行代码，取决于如何计算。
序列化
Boost.Serialization
libs11n
sweet_persist
protobuf
gSOAP - 准确的 XML 序列化
ai-xml - 通过添加单个最小的函数到类，在 XML 间序列化及反序列化。在底层使用 libxml++ 。
C++ XML objects
YAS (Yet Another Serialization)
yaml-cpp
cereal (C++11 serialization)
jios (JSON serialization)
ThorsSerializer (JSON/YAML Input Output Streams)
cppcodec - 唯头文件库，编码 / 解码 base64 、 base32 和十六进制，有一致而灵活的 API （ MIT 许可）
iguana (universal serialization engine)
rpnx-serial - 能（反）序列化如 std::map 、 std::vector 等类型的库
二进制序列化
UBjsonCpp -  基于 C++14 的高性能 UBJson 读写库
binn -  旨在紧凑，快速且易于使用的二进制序列化库，自身是同名格式的实现。
bson-cxx -  BSON 格式的 C++ 实现。
测试
Boost.Test
cppunit
Google Test
Catch2
doctest - 单元测试和 TDD 使用的最轻量的特性丰富的 C++ 单头文件测试框架
lest - 现代的 C++11 原生的单文件唯头文件的轻量单元测试、 TDD 和 BDD 框架（包含 C++98 变体）。
liblittletest - 可移植，单个唯头文件的测试框架
ELFspy - 杜绝假象和间谍的测试 - 仅 Linux
xtd.tunit - Windows 、 macOS 、 Linux 、 iOS 和 Android 上的现代 C++17 单元测试库。官方网站
bandit -  C++11 的对人类友好单元测试
性能评测
Celero
gperftools - “谷歌性能工具” 包含高性能、多线程的 malloc 实现加上评测堆分配和 CPU 利用的工具。
plf::nanotimer - 用于性能评测的最低开销、跨平台的简单定时器类。
Web
libmusicbrainz5
liblastfm
libkcddb
Chromium Embedded
QtWebApp - Java Servlets 所启发的 HTTP (s) Server ，以 C++ 实现
Wt[src][doc]
Tufão
libhttpserver
cpp-jwt
oatpp - 用于创建高性能网络服务的轻量零依赖框架
GPS
gpsd
数据库
redis-plus-plus - 用 C++ 11 编写的 Redis 客户端，支持 Redis Sentinel，Redis Cluster，管道，事务，发布订阅，连接池以及类似于 STL 的接口
cpp-redis - C++11 轻量的 Redis 客户端：异步、线程安全、无依赖、管道化、多平台。
OTL
DTL
libpqxx
lmdb++ - LMDB 嵌入式 B+ 树数据库的 C++11 包装。
mongocxx - MongoDB 的 C++11 驱动库
mysql++
ODB - C++ Object-Relational Mapping (ORM)
Pgfe - PostGres FrontEnd - 现代 C++ 客户端 API 到 PostgreSQL
QUINCE: QUeries IN C++ Expressions (ORM+EDSL)
QxOrm - C++ Qt Object-Relational Mapping (ORM)
SOCI
sqlpp11
SQLAPI++
EasyQtSql -  轻量唯头文件 C++11 库，用 QtSql 快速便捷地进行 SQL 查询
LevelDB -  谷歌开发的、能够处理十亿级别规模 Key-Value 型数据持久性存储的 C++ 程序库。
密码学
Botan
gnutls
openssl
crypto++
TomCrypt
文件元数据
libkexiv2
exiv2
exempi
rarian
文本
编码
uchardet -  实现猜字符串编码的功能，和 python 里的 uchardet 功能基本一样。
win-iconv -  Linux 和 Mac 上的字符集编码转换库 iconv 的 Windows 实现，基于 Win32 字符集转换 API 实现。
格式化
fmt -  printf 不好用，ostream 也不好用，format 好用
分析
PEGTL - 分析表达式文法的模板库
BNFlite - 仅单个头文件的轻量文法分析器库
搜索
clucene
xapian
Step -  Ukkonen 的构建后缀树在线算法， Manber 的构建后缀数组算法。
模板引擎
inja - 现代 C++ 的模板引擎
终端
cwidget
replxx - readline 和 libedit 的替换品，支持 UTF-8 、语法高亮和提示。
配置
gconfmm
libconfig
libconfini - INI 分析器
Boost.Program_options
XML
libxml++
pugixml
tinyxml
tinyxml2 - 另一 TinyXML ，建设中。
Xerces
gSOAP -  XML 数据绑定
JSON
json - 现代 C++ 的 JSON
ArduinoJson - ArduinoJson
jsonme--
ThorsSerializer (JSON/YAML Input Output Streams)
JsonBox
jsoncpp
zoolib
JOST
CAJUN
libjson
nosjob
rapidjson
jsoncons - JSON 与类 JSON 数据结构，含 JSON Pointer 、 JSON Patch 、 JSONPath 、 CSV 、 MessagePack 、 CBOR 、 BSON 、 UBJSON 的唯头文件库。
JSON++
qjson
json-cpp
jansson -  Jansson 是编码、解码及操纵 JSON 数据的 C 库。
json11 -  json11 是 C++11 的轻量 JSON 库，提供 JSON 分析及序列化。
JSON Voorhees - C++ 的杀手 JSON
jeayeson - 非常健全的（唯头文件） C++14 JSON 库
ujson - µjson 是小型的 C++11 、 UTF-8 ， JSON 库
minijson - C++ 无 DOM 且免分配的 JSON 分析及序列化
jios (JSON Input Output Streams)
YAML
yaml-cpp
TOML
toml11 -  基于 C++11 的 TOML 解析库
HOCON
cpp-hocon Pupplet 开发的 HOCON 格式的 C++ 实现。
CSS
mycss -  CSS 解析器
嵌入语言绑定
ChaiScript
ExprTk
lua
sol2
AngelScript - 类似 C++ 的脚本语言。
mozjs
muparser
PythonQt
ScriptCaller - 允许程序员调用 Ruby 脚本的唯头文件库。
v8pp -  将 C++ 函数和类绑定到 V8 JavaScript 引擎中。
嵌入式 / 实时
QP/C++ -  RTOS 内核，双重 GPL
ETL - Embedded Template Library - C++03 ，为少资源平台裁剪的可移植模板库
distortos - 微控制器的面向对象 C++ RTOS
µcuREST - 微控制器的 C++11 REST/JSON 服务器框架
PDF
HARU
PoDoFo
JagPDF
记录
Log4cpp - 用于灵活地记录到文件、系统日志、 IDSA 或其他目标的 C++ 类库 (LGPL)
Log4cplus - 日志 API ，提供日志管理及配置上的线程安全、灵活且有任意粒度的控制。
spdlog - 超快的唯头文件 C++ 日志库
plog - C++ 的可移植且简单的日志，少于 1000 行代码 (MPL2)
Boost.Log
glog - Google 日志库
log4cxx - Apache log4cxx 是 Apache log4j 后的 C++ 模式化记录框架
Pantheios - 诊断日志 API 库，提供类型安全、效率、泛型和可扩展性的结合
Backward - 打印漂亮的 Python 风格栈追踪，带颜色和源代码片段，特别是在崩溃时（ MIT 许可）。

人工智能
stats++
liblinear
Dlib - 机器学习工具
MLPACK - 机器学习包
Shogun - 大规模机器学习工具箱
FANN - 快速人工神经网络库
TensorFlow -  面向所有人的开源机器学习框架
Paddle -  并行化分布式深度学习库
DLDT -  OpenVINO™工具包 - 深度学习部署工具包
TensorRT -  用于在 NVIDIA GPU 和深度学习加速器上进行高性能推理的 C++ 库
NCNN -  腾讯开发的、针对移动平台进行了优化的高性能神经网络推理框架
OpenPose -  实时多人关键点检测库，用于身体，面部，手和脚的检测
ANNetGPGPU -  基于 GPU（CUDA）的人工神经网络库。
btsk -  游戏行为树入门套件。
Evolving Objects -  基于模板的 C++ 演化计算库，可帮助您快速随意地编写自己的随机优化算法。
frugally-deep -  仅头文件的库，用于在 C++ 中使用 Keras 模型。
Genann -  简单神经网络库。
Recast/Detour -  导航网格生成器和浏览器，主要用于游戏。
CNTK -  微软认知工具包（CNTK），一种开源的深度学习工具包。
tiny-dnn -  基于 C++11 的唯头文件、无依赖的深度学习框架。
Veles -  用于快速深度学习应用程序开发的分布式平台。
Kaldi -  语音识别工具包。
版本控制
LibGit2 -  版本控制系统 Git 的核心库。
cpp-semver -  语义化版本号的 C++ 操作库。
排序
Timsort - 模板化的稳定排序函数，对于逆序或半排序的数据，性能优于基于快速排序的算法，包括 std::sort 。 (MIT)
参阅
非 ANSI/ISO 库 的 C 文档

