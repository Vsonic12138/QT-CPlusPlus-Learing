# 环境搭建

## Python环境准备
1. 安装Python 3.x
2. 配置pip和虚拟环境

## Qt环境安装
```bash
pip install PyQt6
pip install PyQt6-tools  # 包含Qt Designer等工具
```

## IDE选择
推荐使用PyCharm或VS Code：
- PyCharm：提供完整的Qt支持
- VS Code：轻量级，配合插件使用

## 验证安装
创建一个简单的测试程序：
```python
import sys
from PyQt6.QtWidgets import QApplication, QWidget

app = QApplication(sys.argv)
window = QWidget()
window.show()
sys.exit(app.exec())
```

## 常见问题
1. 安装PyQt6失败
   - 解决方案...
2. 找不到Qt Designer
   - 解决方案...

## 下一步
完成环境搭建后，我们将开始学习Qt的基础概念。 