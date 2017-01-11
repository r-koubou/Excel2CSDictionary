## Description

Generate a C# source code from xlsx file.

## System requirements

* Python 2.x 3.x
* xlrd (python module) [http://pypi.python.org/pypi/xlrd](http://pypi.python.org/pypi/xlrd)

## How to install xlrd

`pip install xlrd`
see also [http://pypi.python.org/pypi/xlrd](http://pypi.python.org/pypi/xlrd)

## Usage

`python Excel2CSDictionary.py <namespace> <class name> <xlsx filename>`

* namespace:  Generated C# namespace
* class name: Generated C# Class Name
* xlsx filename: source of Excel file (*.xlsx)

**NOTE: C# source code output to stdout.**

e.g.

`python Excel2CSDictionary.py com.example.myapp MyClass Template.xlsx > MyClass.cs`

## XLSX file format

Use a Template.xlsx

## License

See "LICENSE" file.
