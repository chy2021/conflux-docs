# 使用Conflux Portal浏览器插件钱包对数据签名

## 签名方法的历史[#](https://developer.conflux-chain.org/docs/introduction/en/conflux_overview/#history-of-the-signing-methods)

Portal是由MetaMask继承而来，MetaMask中有多种签名方法，你可以在MetaMask文档中查阅所有历史签名方法。

## ConfluxPortal中有何改善[#](https://developer.conflux-chain.org/docs/introduction/en/conflux_overview/#what-changed-in-confluxportal)

* 我们使用`personal_sign`的逻辑来优化`cfx_sign`方法。同时我们推荐使用 `cfx_sign`方法而不是 `personal_sign`方法。
* 目前`signTypedData`, `signTypedData_v1`, `signTypedData_v3`和`signTypedData_v4`的运行原理和MetaMask一样。但是我们计划在主网上线前对其进行优化。

 

