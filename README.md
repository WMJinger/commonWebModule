# ***系统前端说明
- 项目名称：**----系统**
- 前端框架：**layui+jQuert-highchart**
- 启动运行环境命令：1.根目录下安装插件：npm install    2.启动grunt：**grunt**
## 代码规范
- 文件命名格式：短横线
- 代码缩进：2空格
## src目录说明
- common:前端文件，包括样式、图片、脚本等
- css:css编译文件
- font:阿里图标库字体文件
- images:图片
- js:脚本，常用功能脚本存放于common.js,其他脚本为插件文件
- layui: layui框架文件，只读勿改
- less:样式编辑文件
## less目录说明
- component:组件样式，用于存放例如头部、导航等组件样式，每个组件单独一个文件
- public:通用样式，其中
 1. font.less 为字体图标库配置
 2. general.less 为常用样式
 3. reset.less 为样式重置
 4. reset-layui.less 为重置layui框架样式文件，所有关于layui框架样式修改均在此
 5. theme.less 样式主文件，所有个性化样式引用均在此
 6. index.less 首页父框架样式
 7. style.css 样式配置文件，包括主色辅色，换肤等配置
## less变量说明，变量可根据需要自行新增修改
- 外部变量，位于style.less
1. border-color: 线条颜色,
2. @main-color: 主色,
3. @body-color: 网页背景色,
4. @sub-color1:辅色1,
5. @sub-color2:辅色2,
6. @sub-color3:辅色3,
7. @sub-color4:辅色4
- 内部变量,位于theme.less
1. @font-base-color:文本基础色;
2. @font-base-subcolor:文本（弱化）颜色;
3. @font-base-fidcolor:文本（弱化弱化）颜色;
4. @warm-color: 警告色;
5. @error-color: 错误色;
6. @done-color: 成功色;
7. @radius-size:圆角尺寸;
8. @txt-height:文本框高度;
9. @font-base-largesize: 标题文字大小;
10. @font-base-bigsize: 副标题文字大小;
11. @font-base-size: 正文文字大小;
12. @font-base-subsize: 备注文字大小;
13. @block-gap:块间距;
14. @form-gap:表单间距;
15. @images: 样式图片路径;