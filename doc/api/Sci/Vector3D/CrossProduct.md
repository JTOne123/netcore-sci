# SearchAThing.Sci.Vector3D.CrossProduct method
## CrossProduct(Vector3D)
Cross product ( not normalized ) ;            
            a x b = |a| |b| sin(alfa) N ;        
            a x b = |  x  y  z |
                    | ax ay az |
                    | bx by bz |            
            [reference](https://en.wikipedia.org/wiki/Cross_product) ;

### Signature
```csharp
public SearchAThing.Sci.Vector3D CrossProduct(Vector3D other)
```
### Parameters
- `other`: other vector

### Returns

### Remarks
[unit test](/test/Vector3D/Vector3DTest_0019.cs)
            ![](/test/Vector3D/Vector3DTest_0019.png)
