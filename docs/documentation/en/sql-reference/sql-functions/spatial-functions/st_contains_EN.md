\ 35; `St U contains'
Description
'35;'35;' 35; Syntax

`BOOL ST_Contains(GEOMETRY shape1, GEOMETRY shape2)`


Judging whether geometric shape 1 can contain geometric shape 2 completely

'35;'35; example

```
MYSQL > Select ST ^ U contains (ST ^ U Polygon ("Polygon ((0, 10, 10, 10, 10, 10, 0, 10, 0, 0, 0))), ST ^ UPOint (5, 5));
+----------------------------------------------------------------------------------------+
+ 124; ST = U Contains (ST = U Polygon ((0, 10, 10, 10, 0, 10, 0))), ST = UPoint (5.0, 5.0)) 124';
+----------------------------------------------------------------------------------------+
|                                                                                      1 |
+----------------------------------------------------------------------------------------+

MYSQL > Select St ^ U contains (ST ^ U Polygon ("Polygon ((0, 10, 10, 10, 10, 10, 0, 10, 0, 0, 0))), St ^ UPOINT (50, 50));
+------------------------------------------------------------------------------------------+
+ 124; ST = U Contains (ST = U Polygon ((0, 10, 10, 10, 0, 10, 0))), ST = UPoint (50.0, 50.0)) 124
+------------------------------------------------------------------------------------------+
|                                                                                        0 |
+------------------------------------------------------------------------------------------+
```
##keyword
St. John, St. John