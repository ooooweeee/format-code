# 代码风格校验

## **javascript**

- eslint 必须
- prettier 使用 `prettier` 规则检查代码
- eslint-plugin-prettier 让 `eslint` 识别 `prettier`

```sh
npm install -D eslint eslint-plugin-prettier prettier
```

## **typescript**

- typescript 使用 `typescript` 规则检查代码
- @typescript-eslint/parser `typescript` 的解析器
- @typescript-eslint/eslint-plugin 让 `eslint` 识别 `typescript`

```sh
npm install -D @typescript-eslint/parser @typescript-eslint/eslint-plugin typescript
```

## **vue**

- eslint-plugin-vue 让 `eslint` 能校验 `.vue 文件
- eslint-config-prettier 解决 `vue` 等其他校验规则与 `prettier` 冲突

```sh
npm install -D eslint-plugin-vue eslint-config-prettier
```

## **.eslintrc**

- root 表示此配置文件为最顶层配置文件
- parser 使用的解释器
- parserOptions 解释器配置
- env 代码环境
- extends 继承的通用规则
- plugins 插件
- rules 自定义规则
- globals 规避校验的变量
- overrides 对一些文件使用其他的规则

# VSCode 插件

[Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

**_.prettierrc_**

- semi 结尾是否需要分号
- singleQuote 是否使用单引号包裹字符串
- trailingComma 数组或对象中结尾元素后是否需要逗号
- endOfLine 换行符风格
- arrowParens 函数只有一个参数时是否需要括号

[EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

**_.editorconfig_**

- root 表示此配置文件为最顶层配置文件
- indent_style 缩进风格
- indent_size 缩进规格
- end_of_line 换行符
- charset 字符编码
- trim_trailing_whitespace 移除每行结尾空格
- insert_final_newline 文件结尾插入空行
