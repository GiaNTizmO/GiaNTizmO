```csharp
public static class Gamania
{
    static Gamania()
    {
        Console.WriteLine("Hi!");
        __my_dev_info();
        __my_sysadm_info();
    }

    private static Dictionary<string, string> Links = new()
    {
        ["Telegram"] = "https://t.me/NtRaiseException",
        ["Email"] = "contacts@national.shitposting.agency",
    };

    private static void __my_dev_info()
    {
        Console.WriteLine($"🧑🏼‍💻My dev lang Skills: {"C#"} {"C"} {"C++"} {"Java"}");
        Console.WriteLine($"👀Newbie in: {"Dart"} {"Golang"}");
        Console.WriteLine($"⚙️Reversing:{"MS/IL"} {"i386"} {"amd64"}  {"JVM"}");
        Console.WriteLine($"💉Works with: {"Audio and video processing"} {"Fast parallel multithread backends"} {"Network Protocols"}");
        Console.WriteLine($"🔨Most commonly used technologies stack: {"FPM/nFPM"} {"CI/CD"} {"Git"} {"CppSharp"} {"VMProtect"} {"ASP.NET"} {"SignalR"}");
    }

    private static void __my_sysadm_info()
    {
        Console.WriteLine($"🧰My sys admin skills: {"Linux"} {"MS Server"} {"Network administrator"}");
        Console.WriteLine($"🔗Used technologies: {"Virtualization (ESXi/Proxmox/Hyper-V/KVM)"} {"Containers (Docker/LXC)"} {"LAN/VLAN/PPPoE/PPTP/IPoe (Option 82)"} {"LSI IT RAID"} {"FreePBX/Asterisk"} {"Managed Switch (D-Link, Cisco NX-series, SNR)"}");
    }

    public static void Main() => Console.WriteLine("Bye!👋🏻 See you again.🫡");
}
```
