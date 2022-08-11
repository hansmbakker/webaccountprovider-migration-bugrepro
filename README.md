# webaccountprovider-migration-bugrepro

This is a minimal clone of https://github.com/jaimerodriguez/WebAccountProvider/tree/master/SampleProvider to demonstrate that migrating a WebAccountProvider app to Windows App SDK runs into deployment issues.

This element seems not supported in Windows App SDK:
```xml
<Extensions>
    <uap:Extension Category="windows.webAccountProvider">
        <uap:WebAccountProvider Url="https://paxwaptest.azurewebsites.net/" BackgroundEntryPoint="Saso.SampleProvider.BackgroundService.MainTask" />
    </uap:Extension>
</Extensions>
```
