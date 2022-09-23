# twinBASICDocs - Data Types #
Data types help make programming easier. For example, when a variable is declared as a numeric data type, it is safe to perform any of the various mathematical operations on it. If there were no data types, it would be necessary to verify the variable(s) were numeric prior to performing a mathematical operation.

---

> ## <a id="boolean"></a>Boolean ##
> A Boolean data type can be equal to True or False. 
>

> ## <a id="byte"></a>Byte ##
> A Byte data type is an 8 bit, unsigned, 1 byte, number with a range of 0 to 255.
>

> ## <a id="currency"></a>Currency ##
> A Currency data type is an 8 byte number with a range of -922,337,203,685,477.5808 to 922,337,203,685,477.5807.
>

> ## <a id="date"></a>Date ##
> A Date is an 8 byte date/time value with a range from January 1, 100 to December 31, 9999.
>

> ## <a id="decimal"></a>Decimal ##
> A Decimal data type is a 14 byte number with a range of +/-79,228,162,514,264,337,593,543,950,335 with no decimal point; +/-7.9228162514264337593543950335 with 28 places to the right of the decima. The smallest, non-zero, absolute value is +/-0.0000000000000000000000000001.
>

> ## <a id="double"></a>Double ##
> A Double data type is a 64 bit floating point, 8 byte, number with a range of -1.79769313486232E308 to -4.94065645841247E-324 for negative values; 4.94065645841247E-324 to 1.79769313486232E308 for positive values.
>

> ## <a id="integer"></a>Integer ##
> An Integer data type is a 16 bit, signed, 2 byte, number with a range of -32,768 to 32,767.
>

> ## <a id="iunknown"></a>IUnknown ##
> The IUnknown data type is the parent type for all objects.
>

> ## <a id="long"></a>Long ##
> A Long data type (sometimes referred to as a Long Integer) is a 32 bit, signed, 4 byte, number with a range of -2,147,483,648 and 2,147,483,647.
>

> ## <a id="object"></a>Object ##
> An Object data type...
>

> ## <a id="single"></a>Single ##
> A Single data type is a 32 bit floating point number that is 4 bytes and has a range of -3.402823E38 to -1.401298E-45 for negative values and 1.401298E-45 to 3.402823E38 for positive values.
>

> ## <a id="string"></a>String ##
> A String is a dynamically allocated set of alphanumeric characters. I uses 10 bytes of memory, plus one byte for each character in the string. Because twinBASIC dynamically allocates memory for Strings, there is no need to set their length during their initialization. A string can hold approximately four billion characters.
>

> ## <a id="string"></a>String (fixed-length) ##
> A Fixed-length String is a set of alphanumeric characters that ranges in size between 1 and 65,400 characters. However, unlike a variable-length string, fixed-length strings always take up the entire amount of memory allocated to them when they are created, regardless of the length of the data being stored. Attempting to put a longer string than was allocated will cause twinBASIC to raise an error. Fixed-length strings tend to use more memory and are more difficult to manage by the programmer. However, they can be faster than variable-length strings because the memory doesn't need to be re-allocated when the string length changes.
>

> ## <a id="textmetric"></a>TextMetric ##
> A TextMetric is...
>

> ## <a id="variant"></a>Variant ##
> A variant is a generic data type that can store any time of data or object. Variants use 22 bytes of memory. If the Variant contains a string, the Variant will also use one byte of memory per character in the string. If the Variant contains numbers, it can store the same data as a Double.
>

> ## <a id="windowelement"></a>WindowElement ##
> A WindowElement is...
>

