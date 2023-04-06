---
title: Versions
---
Version-specific information:

{{< version "3.10" >}}
This only applies to 3.10.
{{< /version >}}

{{< version "3.10 3.11" >}}
This only applies to 3.10 and 3.11!
{{< /version >}}

--- 

{{< version "3.10 3.11" >}}
Outer Start
{{< version "3.11" >}}
Inner
```aql
RETURN 42
```
{{< /version >}}
Outer End
{{< /version >}}
