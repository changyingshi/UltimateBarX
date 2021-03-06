# Change Log
#### version 0.3.2 (2020.12.11)
* 修复 [issues 16](https://github.com/Zackratos/UltimateBarX/issues/16)
* 修复 sample 中旋转屏幕 crash 的问题
* appcompat 等依赖版本升级

#### version 0.3.1 (2020.12.07)
* 修改 Fragment 实现方式，Fragment 的根布局可以是任何 View
* 增加 `get` 方法，多次调用的时候，可以直接拿到上一次的 config

#### version 0.3.0 (2020.12.02)
* 修改调用方法，废弃旧方法
* 进一步业务分离

#### version 0.2.4 (2020.11.29)
* 优化代码，业务分离
* 修复 Android 4.4 上导航栏默认颜色透明的 bug

#### version 0.2.3 (2020.11.24)
* 修复全面屏手机设置 statusbar 时 navigationbar 变黑的 bug
* 修复全面屏手机不显示导航栏时屏幕下方出现 navigationbar 的 bug
* 优化代码细节

#### version 0.2.2 (2020.08.06)
* 修复多次设置 statusbar 时 navigationbar 错乱的 bug

#### version 0.2.1 (2020.08.06)
* 修改 Fragment 的实现方式（在父布局中实现改为在根布局中实现），Fragment 的根布局是 ViewGroup 即可

#### version 0.2.0 (2020.07.11)
* 增加 Fragment 支持
* 优化代码细节

#### version 0.1.2 (2020.07.09)
* 修复 `bgColorRes` 方法设置导航栏不生效的 bug。

#### version 0.1.1 (2020.07.07)
* Add `bgColorRes` method.

#### version 0.1.0 (2020.07.06)
* Initial release