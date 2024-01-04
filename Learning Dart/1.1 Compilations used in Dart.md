Dart uses a combination of ahead-of-time (AOT) compilation and just-in-time (JIT) compilation, depending on the platform and use case.

1. **Ahead-of-Time (AOT) Compilation:**
    
    - For Flutter mobile applications, Dart primarily uses AOT compilation. This means that Dart code is compiled to native machine code ahead of time, producing a binary executable that can run directly on the target platform without the need for an interpreter or virtual machine at runtime.
    - This approach provides performance benefits as the compiled code is optimized for the specific hardware architecture.
2. **Just-in-Time (JIT) Compilation:**
    
    - For development and certain scenarios, Dart uses JIT compilation. In JIT compilation, the Dart Virtual Machine (VM) translates Dart source code into machine code at runtime, just before executing the program.
    - JIT compilation allows for faster development iterations, as changes to the code can be quickly reflected without the need for a full recompilation.
3. **Hot Reload:**
    
    - Dart, especially in the context of Flutter development, is known for its "hot reload" feature. During development, changes to the code can be injected into the running application, allowing developers to see the effects of their code modifications immediately without restarting the entire application.

In summary, Dart leverages AOT compilation for optimized, standalone production builds and JIT compilation for faster development cycles and dynamic runtime behaviour during the development phase. The combination of these compilation strategies contributes to Dart's flexibility and performance across different use cases.