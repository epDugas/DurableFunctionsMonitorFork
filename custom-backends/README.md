# Custom backends for Durable Functions Monitor

These are Azure Function projects with Durable Functions Monitor 'injected' as a [NuGet package](https://www.nuget.org/profiles/durablefunctionsmonitor). To be used for e.g. monitoring [custom storage providers](https://docs.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-storage-providers).

* [netcore21](https://github.com/microsoft/DurableFunctionsMonitor/tree/main/custom-backends/netcore21) - (legacy) Durable Functions Monitor backend, that runs on .Net Core 2.1.
* [netcore31](https://github.com/microsoft/DurableFunctionsMonitor/tree/main/custom-backends/netcore31) - Durable Functions Monitor backend, that runs on .Net Core 3.1.
* [dotnet7isolated](https://github.com/microsoft/DurableFunctionsMonitor/tree/main/custom-backends/dotnet7isolated) - Durable Functions Monitor .NET 7 Isolated backend.
* [mssql](https://github.com/microsoft/DurableFunctionsMonitor/tree/main/custom-backends/mssql) - Durable Functions Monitor backend to be used with [Durable Task SQL Provider](https://microsoft.github.io/durabletask-mssql/#/).
* [dotnet7isolated-mssql](https://github.com/microsoft/DurableFunctionsMonitor/tree/main/custom-backends/dotnet7isolated-mssql) - Durable Functions Monitor .NET 7 Isolated backend to be used with [Durable Task SQL Provider](https://microsoft.github.io/durabletask-mssql/#/).
* [netherite](https://github.com/microsoft/DurableFunctionsMonitor/tree/main/custom-backends/netherite) - Durable Functions Monitor backend to be used with [Netherite Provider](https://microsoft.github.io/durabletask-netherite/#/).
