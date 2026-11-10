### Anton Kara

I build [Packvium](https://github.com/packvium), a deterministic engine for 3D bin packing
and cartonization. You give it items and boxes, and it returns which box to use and where
each item goes. It works in exact integer arithmetic, gives the same answer every time, and
checks every answer with an independent validator.

It has independent implementations in seven languages, and each one is tested against the
same conformance corpus:

| | |
| --- | --- |
| Python | [packvium-python](https://github.com/packvium/packvium-python) · `pip install packvium` |
| PHP | [packvium-php](https://github.com/packvium/packvium-php) · `composer require packvium/packvium` |
| Rust | [packvium-rust](https://github.com/packvium/packvium-rust) · `cargo add packvium` |
| Node.js and the browser | [packvium-node](https://github.com/packvium/packvium-node) · [packvium-wasm](https://github.com/packvium/packvium-wasm) |
| Java | [packvium-java](https://github.com/packvium/packvium-java) · `com.packvium:packvium` |
| .NET | [packvium-dotnet](https://github.com/packvium/packvium-dotnet) |
| Go | [packvium-go](https://github.com/packvium/packvium-go) · `go get github.com/packvium/packvium-go` |

Documentation and benchmarks are at [packvium.com](https://packvium.com).
