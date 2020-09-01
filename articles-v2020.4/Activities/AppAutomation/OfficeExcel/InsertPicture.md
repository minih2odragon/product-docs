# 插入图片

指定单元格插入图片

## 属性
基本
- **显示名称** ：默认为该组件的名称。支持更改，用户自定义此组件的显示名称
- **失败后继续** ：设置当此组件运行失败时，是否忽略此错误继续运行下一个组件。下拉框选择，当选择"是"时，如果该组件运行时遇到错误，该流程也会继续执行下一个组件，并不会停止；当选择"否"时，如果该组件运行时遇到错误，该流程将会停止执行并抛出错误
- **前延时(毫秒)** ：指定在此组件执行前的等待时间。单位为毫秒（ms）,1000ms = 1s。若此处填写1000，意为上一个组件执行完毕后，等待一秒钟后执行此组件
- **后延时(毫秒)** ：指定在此组件执行后的延迟时间。单位为毫秒（ms）,1000ms = 1s。若此处填写1000，意为此组件执行完毕后，等待一秒钟后执行下一个组件


输入

- **工作表** ：插入图片的目标单元格所属工作表。仅支持字符串变量和字符串
- **单元格** ：被插入图片的目标单元格，支持区域。仅支持字符串变量和字符串
- **图片路径** ：指定插入图片的路径。仅支持字符串变量和字符串

可选项

- **高度(像素)** ：输入被插入图片的高度，单位为像素，为空则使用图片原高度。仅支持Float变量和字符串
- **宽度(像素)** ：输入被插入图片的宽度，单位为像素，为空则使用图片原高度。仅支持Float变量和字符串
