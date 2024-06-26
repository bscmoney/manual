# 回测策略

在创建并保存好交易策略后，您可以使用回测功能来检验策略在历史数据上的表现。以下是详细的回测步骤和相关说明：

### 步骤一：选择策略

1. 登录您的账户（使用Google登录）。
2. 导航到图表页面，选择你创建/收藏的策略。
3. 点击策略名称，加载策略详情。

### 步骤二：设置回测参数

1. **选择回测时间段**：
   * 默认加载最近2000条K线。如果希望测试更长时间段，可以将K线图拖动到最前端，系统会自动加载更早的记录。
2. **选择交易对**：
   * 选择您希望回测的交易对。不同的交易对可能会有不同的市场行为，因此选择合适的交易对非常重要。
3. 选择时间周期：
   * 在K线图中，选择您希望回测的时间周期。

### 步骤三：启动回测

1. **点击“开始回测”按钮**：
   * 确认所有参数设置无误后，点击“开始回测”按钮，系统将自动开始回测过程。
2. **等待回测完成**：
   * 回测过程可能需要一些时间，具体取决于您选择的时间段和交易对。请耐心等待回测完成。

### 步骤四：查看回测结果

回测完成后，系统将生成详细的回测报告。回测结果包含以下内容：

#### 1. 回报率

* **定义**：策略在完整执行后总资金相对于初始金额的百分比。
* **作用**：评估策略的整体盈利能力。

#### 2. 胜率

* **定义**：策略的交易胜率。
* **作用**：衡量策略在总交易次数中的成功率。

#### 3. 盈亏比

* **定义**：策略的盈利与亏损的比例。
* **作用**：评估策略的风险回报比。

#### 4. 交易次数

* **定义**：策略在回测期间的总交易次数。
* **作用**：了解策略的交易频率。

#### 5. 回测结果列表

* **盈利/亏损比例**：每次交易的盈利和亏损比例。
* **入场时间**：每次交易的入场时间。
* **入场价格**：每次交易的入场价格。
* **出场时间**：每次交易的出场时间。
* **出场价格**：每次交易的出场价格。
* **持仓周期**：每次交易的持仓周期。

#### 6. 回测结果自动绘图

* **定义**：回测结果会根据入场时间、止盈/止损条件自动在K线图上绘制图像。
* **作用**：使回测结果更加直观、简单、方便。

### 步骤五：分析回测结果

1. **查看回报率、胜率、盈亏比**：
   * 通过这些关键指标，初步评估策略的表现。
2. **分析每笔交易的详细信息**：
   * 检查回测结果列表中的每笔交易，了解策略在不同市场条件下的表现。
3. **查看K线图上的自动绘图**：
   * 通过图像化的回测结果，更直观地理解策略的入场和出场点。

### 步骤六：优化策略

根据回测结果，您可以对策略进行优化和调整，以提高其在实盘交易中的表现。优化建议包括：

1. **调整触发条件**：
   * 根据回测中表现不佳的交易，适当调整策略的触发条件。
2. **修改止盈/止损条件**：
   * 根据交易的盈亏情况，调整止盈和止损百分比。
3. **更改交易方向**：
   * 如果策略在某个方向上的表现较好，可以考虑专注于该方向的交易。

通过不断的回测和优化，您可以创建出更有效、更稳定的交易策略。
