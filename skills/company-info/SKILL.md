
# 企业基本信息 Skill

这个 Skill 用于存储和提供企业的基本静态信息，帮助 AI 更好地了解企业情况。

## 何时使用此 Skill

- 当需要让 AI 了解企业的基本情况时
- 当需要 AI 根据企业信息提供更贴合的服务时
- 当需要在对话中使用企业相关的信息时

## 如何使用

1. 编辑 `company-config.json` 文件，填入企业的实际信息
2. 在对话中加载此 Skill
3. AI 会根据企业信息提供更贴合的服务

## 企业信息字段说明

### 基本信息
- `company_name`: 企业名称
- `founded_year`: 成立年份
- `industry`: 所属行业
- `headquarters`: 总部地址

### 文化理念
- `mission`: 企业使命
- `vision`: 企业愿景
- `core_values`: 核心价值观（数组）

### 业务范围
- `products_services`: 主要产品/服务（数组）

### 组织架构
- `departments`: 部门设置（数组）
- `employee_count`: 员工规模
- `key_management`: 核心管理层（对象）

### 联系方式
- `phone`: 联系电话
- `email`: 电子邮箱
- `address`: 详细地址

### 社交媒体
- `wechat`: 微信公众号
- `weibo`: 微博账号
- `linkedin`: LinkedIn 账号
- `github`: GitHub 账号
- `website`: 官方网站

### 扩展字段
- `custom_fields`: 自定义信息（对象），可根据需要添加任意企业信息

## 示例使用场景

```
用户: 帮我写一份公司简介
AI: [读取 company-config.json] 根据贵公司的信息，为您生成简介...
```

## 注意事项

- 请妥善保管企业信息，确保不泄露敏感信息
- 定期更新企业信息，保持信息的准确性
- 自定义字段可根据企业实际需要灵活添加
