# Amazing Cultivation Simulator Mobile Mod Directory

**0. Please carefully read the documentation and thoroughly test your MOD before submitting.**  
**Testing methods:**  
1. Use the client to fetch the mod via the git repository address and complete testing on your device. This feature is located at the top right corner of the MOD store.
![IMG](./Docs/github_upload.png)

3. Test using the PC version of ACS: https://store.steampowered.com/app/955900

This is the main directory for mods of Amazing Cultivation Simulator Mobile Edition. Here you can find mod-related information and the list data used by the client to fetch mods.
Everyone is welcome to submit new mod list entries.

## 1. How to Add a New Mod List Entry

You can modify the list by submitting changes to `list.json`.
Add a new entry in `list.json` and fill in the required information, for example:
```json
{
    "name": "ExampleMod",
    "label": "Item,Equipment,Adventure",
    "url": "https://github.com/GSQStudio/acs1_example_mod"
}
```
`label` is used for search filtering. Optional values include:
- OtherWorld
- Reincarnation
- Gong
- Esoterica
- Elixir
- Item
- Equipment
- Building
- Beautify
- Function
- Usability
- Integrated
- Blueprint
- Content
- Adventure
- Language

## 2. How to Organize a Mod Repository

Please refer to the contents of [acs1_example_mod](https://github.com/GSQStudio/acs1_example_mod).

## 3. Other Useful Content

There are useful files in the `Docs` directory, such as all configuration data, API documentation, etc.

---

# 了不起的修仙模拟器移动版Mod主目录

这里是了不起的修仙模拟器移动版的Mod主目录，这里提供了Mod相关的资料以及用于客户端拉取Mod的列表数据。
欢迎大家提交新的mod列表项。

## 0. 请在认真阅读文档并在对MOD进行测试后再提交。
## 测试方法：
1.在客户端使用使用git库地址拉取mod并在你的设备上完成测试。功能位于MOD商店的右上角
![IMG](./Docs/github_upload.png)

2.使用ACS的PC版本进行测试：https://store.steampowered.com/app/955900

## 1. 如何添加一个新的mod列表

你可以通过提交一个关于`list.json`的变动来修改列表。
在`list.json`中新增一个项，填写必须的信息，例如：
```json
{
    "name": "ExampleMod",
    "label": "Item,Equipment,Adventure",
    "url": "https://github.com/GSQStudio/acs1_example_mod"
}
```
`label`用于搜索筛选，可选项有：
- OtherWorld
- Reincarnation
- Gong
- Esoterica
- Elixir
- Item
- Equipment
- Building
- Beautify
- Function
- Usability
- Integrated
- Blueprint
- Content
- Adventure
- Language

## 2. 如何组织一个mod的git库

请查看 [acs1_example_mod](https://github.com/GSQStudio/acs1_example_mod) 的内容。

## 3. 其他有用的内容

在`Docs`目录中有一些有用的文件，例如所有的配置文件数据，API文档等.
