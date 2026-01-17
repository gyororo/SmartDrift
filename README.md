# smart-drift

用于预测性维护的设备参数漂移分析引擎。

### 安装
确保已安装 Python 3 环境，直接克隆仓库即可使用：
```bash
git clone https://github.com/yourusername/smart-drift.git
cd smart-drift
```

### 使用示例
在 `smartdrift.py` 中定义了核心逻辑，可以通过以下方式调用：

```python
from smartdrift import DriftDetector

# 初始化检测器
detector = DriftDetector()

# 输入设备特征指标数据进行分析
result = detector.analyze(data)
print(result)
```

运行测试脚本验证功能：
```bash
python test_smartdrift.py
```

### 说明
* `.Logs/` 目录用于存储运行日志。
* 核心算法逻辑位于 `smartdrift.py`。

### 许可证
本项目采用 MIT 许可证。

