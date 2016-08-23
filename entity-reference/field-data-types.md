# Entity Field Data Types

The following table describes the data types that are used in the entities.

Type | Primitive Type | Description
---|---|---
BigInteger | BigInteger | __BigInteger__ is used for the __RecordId__ field that is included as a system field in every entity. You cannot create fields that use the BigInteger type.
Boolean | Boolean | A value that supports __True__ and __False__.
Currency | Compound | The __Currency__ data type in an entity is implemented as two fields. One field is a decimal value of six decimal places. The other is an enumeration that specifies the currency code – for example, USD or EUR.
Date | DateTime | Only the __Date__ portion of the __DateTime__ type is used by the platform. The __Date__ data type is used when time zone conversion should not be done.
DateTime | DateTime | A date that is combined with a time of day with fractional seconds that is based on a 24-hour clock.
Email | String | __Email__ is stored as a string but is understood by the CDM as a separate type, so that special behavior can be implemented in storage, in the user interface, and in application lifecycle management. The string is stored in Unicode format.
Enumeration | Integer | The integer serves as a reference into one of the standard enumerations.
Image | Binary | GIF and JPG formats are supported.
Integer | Integer | An integer between -2,147,483,648 and 2,147,483,647.
Lookup | [Foreign key] | The value matches the primary key in another table and is used to join information between two tables. It is also known as a foreign key.
MultilineText | String | Multiple lines of text. The maximum length varies, but it is never more than 2,048. The string is stored in Unicode format.
Number | Decimal | A total of 32 digits can be stored, with a maximum of six digits to the right of the decimal point.
NumberSequence | String | __NumberSequence__ is used to automatically generate user-friendly IDs for rows. The ID is a concatenation of a three-character prefix and an automatically incrementing number. For example, the Expense entity has a prefix of “EXP,” so the ExpenseID looks like “EXP001.”
Phone | String | __Phone__ is stored as a string but is understood by the CDM as a separate type, so that special behavior can be implemented in storage, in the user interface. The string is stored in Unicode format.
Text | String | One line of text. The maximum length varies, but it is never more than 128 characters. The string is stored in Unicode format.
Url | String | __Url__ is stored as a string but is understood by the CDM as a separate type, so that special behavior can be implemented in storage, in the user interface. The string is stored in Unicode format.