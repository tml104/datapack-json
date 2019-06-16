# minecraft-json-schema-zh_CN



已更新至：Minecraft Java版 1.14.2

针对 Minecraft 中多种 JSON 文件的 [JSON schema](http://json-schema.org/)。

## 设计规范

- 凡是能够显示指定 `minecraft:` 命名空间的字段，必须指定，不能省略。
- 在编写 `title` 与 `description` 时，请以全角句号（`。`）结尾。

## 支持特性

0. `pack.mcmeta`
1. 进度
2. 战利品表
3. 配方
4. 标签（物品标签、方块标签、函数标签、流体标签、实体类型标签）

## shared 更新方法

将 data generator 生成的 `reports/registries.json` 放置在 `./scripts` 中，然后在终端运行命令 `npm run convert`。

# 协议 - License

本项目以 [CC BY 4.0 协议](https://creativecommons.org/licenses/by/4.0/deed.zh) 进行发布。

This work is released under a [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0)

## 基于 - Based On

本项目基于以 [CC BY 4.0 协议](https://creativecommons.org/licenses/by/4.0/deed.zh)发布的 [Levertion/minecraft-json-schemas](https://github.com/Levertion/minecraft-json-schemas) 项目，作者 [@Levertion](https://github.com/Levertion)。其中所有的英文 `title` 与 `description` 被翻译为了简体中文。

This work is based on [Levertion/minecraft-json-schemas](https://github.com/Levertion/minecraft-json-schemas) created by [@Levertion](https://github.com/Levertion) which is released under a [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/). All `title`s and `description`s in the schema files are translated to Simplified Chinese.
