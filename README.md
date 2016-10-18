# chez-vulkan

Vulkan graphics API binding for Chez Scheme. vulkan.ss is auto-generated by generate-vulkan.ss from vulkan.xml auto-generated by castxml (--castxml-gccxml mode) from vulkan.h. There is no examples, tests or validation codes now.

## Libraries

- `(vulkan)` contains necessities of Vulkan API.
- `(vulkan constants)` defines some Vulkan constants omitted while auto-generating.

Supported platforms are following:

- `(vulkan xlib)`
- `(vulkan win32)` untested yet.

Other platforms are not supoprted now.

## Examples

TODO