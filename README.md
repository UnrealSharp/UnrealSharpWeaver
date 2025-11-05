# UnrealSharpWeaver
UnrealSharpWeaver is a C# IL-weaving toolkit I wrote to inject IL instructions into assemblies so user-written C# can interop with Unreal Engine. It was the core of UnrealSharp, letting managed code talk to native UE APIs.

It’s not officially maintained anymore, but I’m open-sourcing it so it doesn’t just vanish. It shows how UnrealSharp handled interop: injecting native calls, generating property accessors, and marshalling structs between C# and C++. Hopefully it can serve as a useful reference for anyone curious about IL injection or engine integration.
