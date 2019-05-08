### Every single standard Foodcritic rule is documented here with examples


nskdk







#### Link : http://www.foodcritic.io

#### This would be all FCXXX named rule. 


# AIG Custom Foodcritic rules for Chef Cookbooks

![alt tag](http://www.foodcritic.io/images/foodcritic.png)

----------


__## Please find the rules which were not a part of 108 built-in Foodcritic rules in Chef-DK.__




**rule**| - **Description**
------- | ------------------
AIG_DFC001 | -    [Check if CHANGELOG.md in markdown format exist or not.(tag: style)](doc_rules.md)
AIG_DFC002 | -    [Check if LICENSE in markdown format exist or not.(tag: style)](doc_rules.md)
AIG_RFC001 | -    [Resource check with no action. missing default action check.(tag: correctness)](recipe_rules.md)
AIG_RFC002 | -    [Password declaration check in recipe files.(tag: correctness)](recipe_rules.md)
AIG_RFC003 | -    [Execute resource defined without conditional or action :nothing(tag: correctness)](recipe_rules.md)
AIG_RFC004 | -    [Bash resource defined without conditional or action :nothing(tag: correctness)](recipe_rules.md)
AIG_RFC005 | -    [Execute resource used to run chef-provided command(tag: correctness)](recipe_rules.md)
AIG_RFC006 | -    [Templates and CookbookFiles must include # File managed by Chef Cookbook - #{cookbook_name}](recipe_rules.md)
AIG_RFC007 | -    [Check for recipe name with '-'](recipe_rules.md)
AIG_RFC008 | -    [Check for cookbook name with '-'](recipe_rules.md)
AIG_AFC001 | -    [Password declaration check in attribute file](attribute_rules.md)
AIG_UFC001 | -    [Check if spec test files exist for each recipes](spec_rules.md)
AIG_SFC001 | -    [Check if there is valid smoke test files exist or not](smoke_rules.md)
