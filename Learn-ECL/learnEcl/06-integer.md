---
title: Integer
slug: integer
---

# INTEGER

INTEGER data type is an n-byte integer value. Valid values for n are: 1, 2, 3, 4, 5, 6, 7,or 8. Default is 8-bytes.

## Syntax

<pre>
<EclCode
code="[UNSIGNED] INTEGER attribName">
</EclCode>
</pre>

| _Value_    | _Definition_                                    |
| :--------- | :---------------------------------------------- |
| UNSIGNED   | Optional, if omitted the integer is signed.     |
| INTEGER    | OPtional, recommended.                          |
| attribName | The name by which the variable will be invoked. |

**Example**

<pre>
<EclCode
id="TypeInt_Exp"
tryMe="TypeInt_Exp"
code="//INTEGER Examples.

INTEGER Val1 := 12;
INTEGER Val2 := 12.5;

// Notice the decimal point isn't in the result
Val1 + Val2;

Val3 := 67;
Val4 := 10;

Val3 * Val4;"></EclCode>
</pre>

## Value Range

| Size   | Signed Values                                           | Unsigned Values                 |
| ------ | ------------------------------------------------------- | ------------------------------- |
| 1-byte | -128 to 127                                             | 0 to 255                        |
| 2-byte | -32,768 to 32,767                                       | 0 to 65,535                     |
| 3-byte | -8,388,608 to 8,388,607                                 | 0 to 16,777,215                 |
| 4-byte | -2,147,483,648 to 2,147,483,647                         | 0 to 4,294,967,295              |
| 5-byte | -549,755,813,888 to 549,755,813,887                     | 0 to 1,099,511,627,775          |
| 6-byte | -140,737,488,355,328 to 140,737,488,355,327             | 0 to 281,474,976,710,655        |
| 7-byte | -36,028,797,018,963,968 to 36,028,797,018,963,967       | 0 to 72,057,594,037,927,935     |
| 8-byte | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 | 0 to 18,446,744,073,709,551,615 |
