    # 1. 项目空间
    ## 1.1 项目空间（Project）
    工作空间名称|显示名|模式|创建时间|管理员|状态	
    ----|----|----|----|----|----
    `leoao_finance_odps`|乐刻财务项目空间|简单模式（单环境）|2018-07-13 09:30:38|leoao@leoao.com|正常
    `leoao_test_odps`|leoao_test_odps|简单模式（单环境）|2018-06-05 15:15:06|leoao@leoao.com|正常	
    `leoao_biz_odps`|leoao_biz_odps|简单模式（单环境）|2018-10-12 14:04:58|leoao@leoao.com|正常
    `leoao_produce_odps`|leoao_produce_odps|标准模式（开发跟生产隔离）|2018-06-05 15:18:14|leoao@leoao.com|正常
    ## 1.2 数据集成（Resource）
    工作空间名称|数据源
    ----|----
    `leoao_finance_odps`|[数据源URL（请切换项目空间）](https://di2-cn-shanghai.data.aliyun.com/#/project/datasource-list)
    `leoao_test_odps`|[数据源URL（请切换项目空间）](https://di2-cn-shanghai.data.aliyun.com/#/project/datasource-list)	
    `leoao_biz_odps`|[数据源URL（请切换项目空间）](https://di2-cn-shanghai.data.aliyun.com/#/project/datasource-list)
    `leoao_produce_odps`|[数据源URL（请切换项目空间）](https://di2-cn-shanghai.data.aliyun.com/#/project/datasource-list)

    # 2. 数据开发
    ## 2.1 `leoao_test_odps`（简单模式）
    ### 2.1.1 数据同步
    1. apidoc
    描述：临时任务，操作：`后续删除或修改`

    2. odps_to_my_sql_dap
    描述：DeepInsight同步任务，操作：无

    3. redis
    描述：Redis同步任务，操作：`后续删除或修改`

    4. SAAS库
    描述：SAAS系统报表，操作：无



