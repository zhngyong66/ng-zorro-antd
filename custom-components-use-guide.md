##1.antd自定义组件的基本使用简要说明

|             |                                                            |                                                              |
| ----------- | ---------------------------------------------------------- | :----------------------------------------------------------- |
| 组件        | 基本使用                                                   | 注意事项                                                     |
| button      | <button nz-button nzType="primary">Primary</button>        | 默认的focus状态在鼠标up时,取消了focus状态.如果想使用的话可以加上 needFocus属性. focus样式: // 按钮选中时候的颜色 .selectClass {  color: #4BAFD7;  box-shadow: 0px 1px 0px rgba(255, 255, 255, 0.12), 0px 0px 4px rgba(255, 255, 255, 0.2);  border-radius: 4px;  border: 1px solid rgba(0, 0, 0, 0.2);  background: rgb(51, 51, 51); } |
| checkbox    | 同官网:   https://ng.ant.design/components/checkbox/zh     |                                                              |
| datePicker  | 同官网:   https://ng.ant.design/components/date-picker/zh  |                                                              |
| form        | 同官网:   https://ng.ant.design/components/form/zh         |                                                              |
| input       | 同官网:   https://ng.ant.design/components/input/zh        |                                                              |
| InputNumber | 同官网:   https://ng.ant.design/components/input-number/zh |                                                              |
| radio       | 同官网:   https://ng.ant.design/components/radio/zh        | 注意nzValue的单向和双向绑定的使用区别, 以及分组使用时候的事项,具体用法参照官网 |
| select      | 同官网:   https://ng.ant.design/components/select/zh       |                                                              |
| slider      | 同官网:   https://ng.ant.design/components/slider/zh       |                                                              |
| table       | 同官网:   https://ng.ant.design/components/table/zh        | 注意固定头和列时候的样式处理 注意分页和滚动条位置的单独处理  |
| tree        | 同官网:   https://ng.ant.design/components/tree/zh         | 注意选择和不可选择时候的样式变化                             |
| modal       | 同官网:   https://ng.ant.design/components/modal/zh        | 取消了默认选择第一个表单控件为focus状态                      |
| progress    | 同官网:   https://ng.ant.design/components/progress/zh     | 只更改了标准进度条的样式                                     |

##2.每次更新antd自定义库之后, 会将相应的tgz的包文件上传到项目中, 使用时只需要:

 	npm install ./utils/ng-zorro-antd.tgz
