# MetricData *:Object*

## 键值

### Value? *:number*

可选(但Value与Values必选且只选其一)，上报的数值

### Values? *:number[]*

可选(但Value与Values必选且只选其一)，上报的数值组与频率，与Counts一起使用，Counts数组长度与Values相同，相应键值代表数值出现的频率。
例如Value: [10, 20], Counts: [2, 3]代表 数值10出现2次，数值20出现三次

### Counts? *:number[]*

如上Values的介绍

### Unit? *:Unit*

可选，数值单位（暂不使用）

### StatisticalValue? *:IStatisticalValue*

### Timestamp *:Timestamp*

可选，数值时间戳

### Dimensions? *:IDimension[]*

可选，KeyName键值，区分数据记录域

### Metas? *:IMeta[]*

可选，KeyName键值，数据上报的额外信息
