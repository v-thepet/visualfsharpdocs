# CompilerServices.RuntimeHelpers Module (F#)

A group of functions used as part of the compiled representation of F# sequence expressions.

**Namespace/Module Path:** Microsoft.FSharp.Core.CompilerServices

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax

```
module RuntimeHelpers
```

## Remarks

## Values


|Value|Description|
|-----|-----------|
|[CreateEvent](http://msdn.microsoft.com/en-us/library/8eca0f7b-84f9-4ffd-a9c4-4b85937b81e8)<br />**: ('Delegate -&gt; unit) -&gt; ('Delegate -&gt; unit) -&gt; ((obj -&gt; 'Args -&gt; unit) -&gt; 'Delegate) -&gt; IEvent&lt;'Delegate,'Args&gt;**|Creates an anonymous event with the given handlers.|
|[EnumerateFromFunctions](http://msdn.microsoft.com/en-us/library/a7e754e2-4766-4d17-990a-61bc858393c6)<br />**: (unit -&gt; 'T) -&gt; ('T -&gt; bool) -&gt; ('T -&gt; 'U) -&gt; seq&lt;'U&gt;**|The F# compiler emits calls to this function to implement the compiler-intrinsic conversions from weakly typed **T:System.Collections.IEnumerable** sequences to typed sequences.|
|[EnumerateThenFinally](http://msdn.microsoft.com/en-us/library/8d9fe619-a247-4de1-9cc8-a0f54517cef6)<br />**: seq&lt;'T&gt; -&gt; (unit -&gt; unit) -&gt; seq&lt;'T&gt;**|The F# compiler emits calls to this function to implement the **try...finally** construct for F# sequence expressions.|
|[EnumerateUsing](http://msdn.microsoft.com/en-us/library/b25ee067-a8ad-4b81-a58c-072f127d69f5)<br />**: 'T -&gt; ('T -&gt; 'Collection) -&gt; seq&lt;'U&gt;**|The F# compiler emits calls to this function to implement the **use** keyword for F# sequence expressions.|
|[EnumerateWhile](http://msdn.microsoft.com/en-us/library/9f48435f-2754-42e2-8d1a-9d002b7e60b5)<br />**: (unit -&gt; bool) -&gt; seq&lt;'T&gt; -&gt; seq&lt;'T&gt;**|The F# compiler emits calls to this function to implement the **while** keyword for F# sequence expressions.|

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Microsoft.FSharp.Core.CompilerServices Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core.CompilerServices+Namespace+%28FSharp%29.md)
