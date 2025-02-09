# CommandManager class

特性指令管理器

```csharp
public sealed class CommandManager
```

## Public Members

| name | description |
| --- | --- |
| [ServiceIsRunning](CommandManager/ServiceIsRunning.md) { get; } | 指令服务正常运行标识 |
| [DeleteDynamicCommand](CommandManager/DeleteDynamicCommand.md)(…) | 删除指定ID的指令 |
| [GetInstance&lt;T&gt;](CommandManager/GetInstance.md)(…) | 获取已注册过的实例 |
| [MappingCommands](CommandManager/MappingCommands.md)(…) | 自动注册所有指令 |
| [RegisterGroupDynamicCommand](CommandManager/RegisterGroupDynamicCommand.md)(…) | 动态注册指令 (2 methods) |
| [RegisterPrivateDynamicCommand](CommandManager/RegisterPrivateDynamicCommand.md)(…) | 动态注册指令 (2 methods) |
| [TryDisableCommandGroup](CommandManager/TryDisableCommandGroup.md)(…) | 尝试禁用指令组 |
| [TryEnableCommandGroup](CommandManager/TryEnableCommandGroup.md)(…) | 尝试启用指令组 |

## See Also

* namespace [Sora.Command](../Sora.md)

<!-- DO NOT EDIT: generated by xmldocmd for Sora.dll -->
