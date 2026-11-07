# edu-exam-paper-generator

- 产品名称：`edu-exam-paper-generator`
- 产品编号：`JLZ-EDU-SK-030`
- 产品类型：Skill
- 所属业务板块：03 教学教研中心
- 作者/维护方：广州金励泽科技服务有限公司
- 研发版本：1.0.2
- 当前状态：**G9_R2_PRE_RELEASE_ACCEPTED / MODEL_RUNTIME_NOT_VERIFIED**
- 产品规格书：[PRODUCT_SPEC.md](PRODUCT_SPEC.md)
- 使用说明：[USAGE.md](USAGE.md)
- 安装包：[`dist/edu-exam-paper-generator-v1.0.2.zip`](dist/edu-exam-paper-generator-v1.0.2.zip)

## 产品功能

按年级、学科、范围和难度生成试卷。

- 主要输入：年级学科、考试范围、教材版本、题量、题型、难度、时间和答案要求
- 主要输出：试卷、答题卡建议、参考答案、评分标准、难度分布和来源检查

## 本地验证

- 测试案例：[tests/TEST_CASES.md](tests/TEST_CASES.md)
- 结构测试：[tests/validate_package.ps1](tests/validate_package.ps1)
- 测试结果：[test-results/v1.0.2.json](test-results/v1.0.2.json)

本地通过证明文件结构、产品契约、分层测试、确定性脚本和安装包完整性通过；生成式模型行为仍为 MODEL_RUNTIME_NOT_VERIFIED，不代表 WorkBuddy 解析、安装、调用或审核通过。

## 依赖与数据

- 第三方运行依赖：无。
- 默认外部API：无。
- 不要求用户提供API Key。
- 仅处理用户主动提供或明确授权的数据。

## 开源许可证

License: Apache-2.0.

本仓库为免费开放的开源项目。任何人均可依照 Apache License 2.0 使用、修改和分发本项目内容。完整法律条款见 [LICENSE](LICENSE)。
