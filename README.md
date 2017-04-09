# FM-SetFieldsWithValues
A standard re-usable script for setting any number of fields with any values, for everyday use in any FileMaker file
version 1.00

copyright Benedick Miller benlight.miller@gmail.com

### Requirements

Required Custom Functions:
CustomList()
#(), #Assign()

The required Custom Functions can be copied from SetFieldsWithValues.fmp12 available at https://github.com/metalox/FM-SetFieldsWithValues
 
CustomList() is also available here:
http://www.briandunning.com/cf/868

#() ans #()Assign etc. are also available here:
https://github.com/filemakerstandards/fmpstandards/tree/master/Functions/%23Name-Value

### Introduction

The setFieldsWithValues script can be used as is on any layout in any file. The script is driven by the script parameter supplied.
 
Rather than creating many similar scripts to perform similar tasks on different layouts here a single script script is re-useable anywhere by suppying specific instructions in the script parameter when the script is run. The script parameters can be created, edited and saved as snippets in a text editor. The intention is to save development time and to simplify the FileMaker solution by using abstraction.

Basic usage is to set a field with a value, or with no value to clear the field. Many fields may be set with many values at the same time. In addition the set field actions may be preceded by a confirmation dialog and succeeded by various everyday actions such as commit recoord, refresh widow or portal or object and go to object.

### Usage

Please see the main script: SetFieldsWithValue: setFieldsWithValues() which contains the usage documentation

### Installation

Make sure to install the required custom functions BEFORE installing the scripts folder

1. Install the required Custom Functions CustomList(), #(), #Assign()

2. Create a folder named Modules in the scripts workspace, if it does not already exist

3. Copy the SetFieldsWithValues script folder into the Modules folder

Check the FileMaker import.log file at each stage for errors.
 
 ### TO DO
 
* Replace the required customFunctions with sub-scripts or script steps if possible
