# JESUS EDUARDO UICAB BRICEÑO 

Data is complex, and all data is different. Accordingly, DataTables has a wealth of options which can be used to configure how it will obtain the data to display in the table, and how it processes that data.

There are three core concepts in how DataTables handles data, which are discussed in detail on this page:

- Processing mode
- Data types
- Data sources


## Numerical data. 
These data have meaning as a measurement, such as a person’s height, weight, IQ, or blood pressure; or they’re a count, such as the number of stock shares a person owns, how many teeth a dog has, or how many pages you can read of your favorite book before you fall asleep. (Statisticians also call numerical data quantitative data.)

## Categorical data: 
Categorical data represent characteristics such as a person’s gender, marital status, hometown, or the types of movies they like. Categorical data can take on numerical values (such as “1” indicating male and “2” indicating female), but those numbers don’t have mathematical meaning. You couldn’t add them together, for example. (Other names for categorical data are qualitative data, or Yes/No data.)

## Boolean type
The Boolean type represents the values true and false. Although only two values are possible, they are rarely implemented as a single binary digit for efficiency reasons. Many programming languages do not have an explicit Boolean type, instead interpreting (for instance) 0 as false and other values as true. Boolean data refers to the logical structure of how the language is interpreted to the machine language. In this case a Boolean 0 refers to the logic False. True is always a non zero, especially a one which is known as Boolean .

## Numeric types
Such as:

The integer data types, or "non-fractional numbers". May be sub-typed according to their ability to contain negative values (e.g. unsigned in C and C++). May also have a small number of predefined subtypes (such as short and long in C/C++); or allow users to freely define subranges such as 1..12 (e.g. Pascal/Ada).
Floating point data types, usually represent values as high-precision fractional values (rational numbers, mathematically), but are sometimes misleadingly called reals (evocative of mathematical real numbers). They usually have predefined limits on both their maximum values and their precision. Typically stored internally in the form a × 2b (where a and b are integers), but displayed in familiar decimal form.
Fixed point data types are convenient for representing monetary values. They are often implemented internally as integers, leading to predefined limits.
Bignum or arbitrary precision numeric types lack predefined limits. They are not primitive types, and are used sparingly for efficiency reasons.


## String and text types
Such as:

A character, which may be a letter of some alphabet, a digit, a blank space, a punctuation mark, etc.
A string, which is a sequence of characters. Strings are typically used to represent words and text.
Character and string types can store sequences of characters from a character set such as ASCII. Since most character sets include the digits, it is possible to have a numeric string, such as "1234". However, many languages treat these as belonging to a different type to the numeric value 1234.

Character and string types can have different subtypes according to the required character "width". The original 7-bit wide ASCII was found to be limited, and superseded by 8 and 16-bit sets, which can encode a wide variety of non-Latin alphabets (such as Hebrew and Chinese) and other symbols. Strings may be either stretch-to-fit or of fixed size, even in the same programming language. They may also be subtyped by their maximum size.

### Data characteristics: raw and clean.
Raw data: Is data that has not been processed for use. A distinction is sometimes made between data and information to the effect that information is the end product of data processing. Raw data that has undergone processing is sometimes referred to as cooked data.
## local remote remote repositories

Clean data: Is the process of detecting and correcting (or removing) corrupt or inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data.
URL: A Uniform Resource Locator, colloquially termed a web address, is a reference to a web resource that specifies its location on a computer network and a mechanism for retrieving it. A URL is a specific type of Uniform Resource Identifier, although many people use the two terms interchangeably

APIS: An application programming interface is a computing interface which defines interactions between multiple software intermediaries. It defines the kinds of calls or requests that can be made, how to make them, the data formats that should be used, the conventions to follow, etc.


# data formats

## CSV
CSV (Comma Separated Values) files are commonly used to exchange tabular data between systems in plain text. They typically contain a header row that provides the column names for the data, but these are considered semi-structured. This is because CSV files cannot naturally represent hierarchical or relational data. Data relationships are typically controlled with multiple CSV files, where the foreign keys are stored in columns of one or more files, but the relationships between those files are not expressed in the format itself. Files in CSV format can use other delimiters than commas, for example tabs or spaces.

 ## JSON
JSON (JavaScript Object Notation) data is represented as key and value pairs in a semi-structured format. JSON is often compared to XML as both are capable of storing data in a hierarchical format with the rendered child data aligned to its parent. Both are self-describing and readable, but JSON documents tend to be much smaller, which has led to their popular use in online data exchange, especially with the advent of REST-based web services.


## CSV or JSON
CSVs are typically used for the export and import of data or for processing for analysis or machine learning. JSON files have the same benefits, but are more common in active data exchange solutions. JSON documents are often sent by web and mobile devices for online transactions, by IoT (internet of things) devices for one-way or two-way communications, or by client applications communicating with SaaS and PaaS services or architectures without server.
___



