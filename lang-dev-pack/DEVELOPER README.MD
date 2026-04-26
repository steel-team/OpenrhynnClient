# CLIENT
### folder  CLIENT
### Language files description
langs/`name`_lettertable_little.txt - text file with all letters little case from language `name`
langs/`name`_lettertable_big.txt - text file with all letters big case from language `name`
langs/`name`_stringtable.txt - text file with main lang text data
langs/`name`_descr.txt - text file with font description:`noOfChars` `charWidth` `charHeight` `spaceID`
fonts/`name`.png

# SERVER (Legacy)
### folder SERVER/Legacy(Sharp)
### Language files description
Data/Languages/`name`.xml - translation file

# SERVER (Current)
### folder SERVER/Current(Java)
### Language files description
localization/`name`.json - translation file


****
`name` - name of your language

When you done translation add space into file CLIENT/lang_list.txt and then `name`
Also add definition to SERVER/Current(Java)/localization/definition.json